---
layout: post
title: 코드스테이츠 둘째 주
---

지난 주는 멘붕의 시작이었다면, 이번 주는 멘붕의 연속. 특히 배열 파트에 와서는 진도를 따라잡기 위해서는 하루에 3시간이 아니라 거의 4시간씩 공부했다.
무엇보다 힘든 건 과제를 하면서 계속 진도가 나가지 않는 것이다. 삽질하다가 문득 시계를 보면 40분 지나가있고 막.. 두 문제 풀었는데 한시간 훌쩍 지나갔고..
이번 주에 가장 힘든 과제는 4.객체 - 12. extends 였다.

{
for (var key in obj2) {

    if (obj1[key] == undefined) {
        obj1[key] = obj2[key];
    }
}

이 3줄을 만들어내기까지 얼마나 많은 시간이 걸렸는지.....
= 은 이퀄의 의미가 아니라 값을 대입하는 거라는 걸 머리로는 알고있는데, 막상 코드를 짤 때에는 자꾸만 a = b 하면 a는 b다라고 생각이 굳어져버린다.

for 문에서 in 을 사용하면 오브젝트 안의 키를 하나 하나 대입하면서 계속 코드가 실행되고, 그 과정에서 obj1[key]를 입력하면 obj1에 key가 없을 경우 key가 생성되지만 값은 없어서 undefined가 된다.
만약 obj1에 key가 있으면 obj1[key]를 입력했을 때 값이 나올테니까 그 때에는 아무 실행 없이 다음 키로 넘어간다.
이 간단해보이는 게 왜이리 어려웠던지.

이제 5번, 6번 과제들 풀어야하는데 눈 앞이 깜깜하다! 
