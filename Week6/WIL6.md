웹스터디 6주차 과제

1) 스테이지 1 
#pond {
  display: flex;
justify-content: flex-end;
}

2) 스테이지 2
#pond {
  display: flex;
justify-content: center;
}

3) 스테이지 3
#pond {
  display: flex;
justify-content: space-around;
}

4) 스테이지 4
#pond {
  display: flex;
justify-content: space-between;
}

5) 스테이지 5
#pond {
  display: flex;
align-items: flex-end;
}

6) 스테이지 6
#pond {
  display: flex;
justify-content: center;
align-items: center;
}

7) 스테이지 7
#pond {
  display: flex;
justify-content: space-around;
align-items: flex-end;
}

8) 스테이지 8
#pond {
  display: flex;
flex-direction: row-reverse;
}

9) 스테이지 9
#pond {
  display: flex;
flex-direction: column;
}

10) 스테이지 10
#pond {
  display: flex;
flex-direction: row-reverse;
justify-content: flex-end;
}

11) 스테이지 11
#pond {
  display: flex;
justify-content: flex-end;
flex-direction: column;
}

12) 스테이지 12
#pond {
  display: flex;
flex-direction: column-reverse;
justify-content: space-between;
}

13) 스테이지 13
#pond {
  display: flex;
flex-direction: row-reverse;
justify-content: center;
align-items: flex-end;
}

14) 스테이지 18
#pond {
  display: flex;
flex-wrap: wrap;
}

15) 스테이지 19
#pond {
  display: flex;
flex-wrap: wrap;
flex-direction: column;
}

16) 스테이지 20
#pond {
  display: flex;
flex-flow: column wrap;
}



+) 레퍼런스 페이지 20번
flexbox는 모던 웹을 위하여 제안된 기존 layout보다  더 세련된 발식의 니즈에 부합하기 위한 CSS3의 새로운 layout 방식이다. 요소의 사이즈다 불명확하거나 동적으로 변화할 때에도 유연한 레이아웃을 실현할 수 있으며 복잡한 레이아웃이라도 적은 코드로 보다 간단하게 표현할 수 있다.
 flexbox 레이아웃은 flex item이라 불리는 복수의 자식 요소와 이들을 내포하는 flex-container 부모 요소로 구성된다.
 - flex-direction 속성은 flex 컨테이너의 주축 방향을 설정한다. (row, row-reverse, clolumn, column-reverse)
 - flex-wrap 속성은 flex컨테이너의 복수 flex item을 1행으로 또는 복수행으로 배치한다. (nowrap, wrap, wrap-reverse)
 - flex-flow 속성은 flex-direction 속성과 flex-wrap 속성을 설정하기 위한 shorthand이다. 기본값은 row nowrap이다.
 - justify-content는 flex container의 주축을 기준으로 flex item을 수평 정렬한다. (flex-start, flex-end, center, space-between, space-around)
 - align-items는 flex item을 flex container의 수직 방향(cross axis)으로 정렬한다. align-items 속성은 모든 flex item에 적용된다. (stretch, flex-start, flex-end, center, baseline)
 - align-content는 flex container의 cross axis를 기준으로 flex item을 수직 정렬한다. (stretch, flex-start, flex-end, center,space-between, space-around)
