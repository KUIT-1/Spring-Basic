# spring-basic

<br/>

7️⃣ [7주차 워크북 - 스프링 IoC, DI, MVC](https://fearless-texture-68a.notion.site/Server-7-IoC-DI-MVC-a2b39eaa786b4cd493ad6e3822266a24)
- spring 전환

<br/>

---

### main

> 미션 수행 장소

<br/>

### servlet

> 6주차 미션 + HandlerAdapter 구현 코드

#### v1

- ControllerV1 : ModelAndView 객체를 반환하는 Controller
- 실행 : `localhost:8080/v1/…`

#### v2

- ControllerV2 : 뷰 이름(String viewName)을 반환하는 Controller
- 실행 : `localhost:8080/v2/…`

#### v3

- 두 종류의 Controller를 전부 사용하기 위해 HandlerAdapter를 도입
- 실행
    - ControllerV1 : `localhost:8080/v3/v1/…`
    - ControllerV2 : `localhost:8080/v3/v2/…`

<br/>

### springbasic

> 미션 구현 코드
