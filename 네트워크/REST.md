# REST

**REST(REpresent State Transfer)**란 웹에 존재하는 모든 자원(이미지, 동영상, DB)에 고유한 URL을 부여하여 활용하는 것을 의미한다.

## REST 구성요소

1. 자원(Resource), URL

   모든 자원은 고유한 ID를 가지며 클라이언트는 각 자원의 상태를 조작하기 위해 요청을 보낸다.

2. 행위(Verb), Method

   클라이언트는 URL을 이용해 자원을 지정하고 자원을 조작하기 위해 Method를 사용한다.

3. 표현(Representation)

   클라이언트가 서버로 요청을 보냈을 때 응답 자원의 상태를 `Representation`이라고 한다.

## HTTP 메소드

| 메소드 이름 | 설명                                          |
| ----------- | --------------------------------------------- |
| GET         | Read: 정보요청                                |
| POST        | Create: 정보 입력                             |
| PUT         | Update: 정보 업데이트 (데이터 전체를 바꿀 때) |
| PATCH       | 정보 업데이트 (데이터의 일부만 바꿀 때)       |
| DELETE      | Delete: 정보 삭제                             |

## RESTful

REST 아키텍쳐를 준수해 설계된 API
