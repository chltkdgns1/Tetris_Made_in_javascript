# Tetris_Made_in_javascript

https://www.youtube.com/watch?v=QDnL7QKxrK8
</br>

# 제작 이유

##### js 는 프론트 앤드부터 백앤드까지 많은 부분을 담당하고 있습니다.
##### 최근에 node.js 를 처음 사용해보면서 apache 로 서버를 구현했던 것에 비해 상당히 간편함을 느끼고 
##### node.js 를 비롯한 react 와 vue 를 겪게되면서 js 에 대한 공부가 필요하겠다고 생각이 들었습니다.

##### 따라서 간단한 프로젝트로 js 로 테트리스를 구현해보았습니다.
##### 사실, c++ 로도 테트리스는 구현한적이 없어서 어떤 언어로든 진행하고 싶었는데 이번에 구현하게 되었습니다.

</br>

# 제작 기간

##### 6시간

</br>

# 사용했던 것

##### js 에 대해서 잘 몰라서 어떤 특정 API 를 사용했다고 말은 못하겠습니다.
##### js 코딩 쪽으로 자신은 있지만, 개념적인 부분이나 js 적으로 코딩을 하는 느낌은 스스로도 받지 못했습니다.
##### 따라서 제가 쓰면서 구글링했던 부분은 canvas 부분을 사용했던 것입니다.
##### 이미지 태그를 기반으로 css 이동하여 구현을 하려고 했으나 실패하게 되었고, 따라서 프린팅하는 쪽이 canvas가 훨씬
##### 편하다고 생각해서 canvas 를 사용하게 되었습니다.

##### 기본적으로 이미지 태그로 css 를 수정했을 때 다른 부분들까지 구현이 가능할 것 같았지만, 블록 한 줄이 사라지는 효과를 줄 때,
##### 이미지 태그의 부분이 삭제되는 처리를 제 짧은 js 지식으로 처리가 불가능하여 canvas 를 사용했습니다.

##### 결론적으로, ㄱ,ㄴ 이런 블록 이미지 보단 ㅁ 형태의 제일 작게 분리된 것을 가지고 2차원 canvas 위에 출력해주는 형태로 진행했습니다.

</br>

# 어려웠던 점

##### 어려웠던 점은 c++ 에서 예전에 게임 구현 경험이 있었습니다.
##### 보통 게임 종료까지 무언가를 움직이기 때문에 큰 loop 가 필요하고 이 loop 는
##### while(1) or for(;1;) 로 구현을 해주었습니다.

##### 그리고 getTickCount() 함수를 사용해서 반복문 내부에서 시간차이를 구해서 1초가 지나면 블록이 아래로 떨어지는 로직을 
##### 구현하려고 하였고, 실제 js 에 적용했는데 웹 페이지 자체가 멈춰버리는 현상이 발생했습니다.

##### 일단 웹 페이지(? 개념 부족으로 웹페이지가 아닐수 있습니다.)가 메인스레드 한 개로 실행되는 구조인 것을 몰라서,
##### while(1) 로 무한 루프를 돌리니 다른 버튼 클릭이라든지 크롬 웹 페이지의 f12 같은 것들도 이용이 제한되었습니다.
##### while 을 이용한 흐름의 제한은 더욱 상위의 어떤 곳에서 이루어지는 것 같았고 이를 제공하는 setInterval 함수를 이용하게 되었습니다.

##### 따라서 c++ 과 다르게 실행 흐름도 달랐기 때문에 적응하는데 시간이 걸렸지만 나름 좋은 공부가 되었던 것 같습니다.

</br>

# 아쉬웠던 점

##### 아쉬웠던 점으로는 js 를 너무 js 느낌을 살리지 못했다라는 느낌을 받았습니다.
##### 사실 책을 위주로 공부를 한게 아니다보니(책을 보긴 했는데, 학교 전자책이라, 년도나 책들이 원하는 것이 없었습니다.) 제한 사항이 있었고,
##### 아직 익숙하지 않은게 사실이라 좀 더 깊은 공부가 필요할 것 같습니다.






