[https://ofcourse.kr/css-course/%EC%86%8D%EC%84%B1](https://ofcourse.kr/css-course/속성)



## width, height 속성

요소의 크기

border의 크기와는 다름





## margin, padding 속성

margin은 border 기준 바깥쪽 여백

padding은 border 기준 안쪽 여백





## box-sizing 속성



#### content-box

기본적으로 box의 전체 너비가 padding와 width가 더해져서 그려짐

default값이 content-box이기 때문



#### border-box

box-sizing속성을 border-box로 주면 width를 border기준으로 줄 수 있음



#### content-box에서 width:100%일 때의 문제

CSS에서 width 속성을 100%로 주면 **부모**의 width 만큼 너비가 설정됩니다. 하지만 content-box일 때 `width: 100%`에 이어 padding이나 border를 주게 될 경우 부모의 영역을 초과해서 너비가 정해지는 문제가 생길 수 있습니다.

이런 문제를 해결하기 위해서는 `box-sizing`을 `border-box`로 설정하거나 width를 `auto`로 설정하여 해결할 수 있습니다. width의 기본 값은 `auto`이므로 width를 아예 적어주지 않아도 정상적으로 동작합니다.





## text-align 속성

text의 정렬 방향

- left, right, center
- justify: 양쪽정렬(자동 줄 바꿈시 오른쪽 경계선 부분 정리)





## background



#### background-repeat

background-image가 컨테이너보다 작으면 이미지가 반복되어 출력되는데, 이 때 반복 여부를 지정할 수 있다.

background-repeat: no-repeat



#### background-position

일반적으로 background-image는 왼쪽 위부터 이미지를 출력한다.

px단위로 간격을 줄 수 있고, left, top, center, bottom, right도 가능하다.





## border

```css
#box{
	border: 4px dotted green;
	border-bottom: 5px solid blue;
}
#box3{
    border-radius: 20px 0 10px 50px;
}
```





## display 속성

display 속성은 요소를 어떻게 보여줄지를 결정한다.

주로 4가지 속성값이 쓰이는데, 태그마다 기본값이 다르다.

- none
- block
- inline
- inline-block



#### none

요소를 랜더링하지 않도록 설정한다. visibility 속성을 hidden으로 설정한 것과 달리, 영역도 차지하지 않는다.



#### block

`<div>`, `<p>`, `<h#>`, `<li>` 등이 block

기본적으로 가로 영역을 모두 채운다. (줄 바꿈처럼)

width, height 속성을 지정할 수 있다. 



#### inline

`<span>`, `<a>` 등이 inline

block과 달리 줄 바꿈이 되지 않고, width와 height을 지정할 수 없다.



#### inline-block

줄 바꿈이 되지 않지만 크기를 지정할 수 있다.





## float 속성

