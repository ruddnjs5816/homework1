# homework1

1. 수정, 삭제 API의 request를 어떤 방식으로 사용하셨나요? (param, query, body)
-수정은 RequestBody를 통해서 진행했고, 삭제는 RequestParam을 통해서 진행했다.
-RequestBody는 XML, JSON, 등의 데이터를 담는다.
-RequestParam은 주소에 포함된 변수를 담는다.


2. 어떤 상황에 어떤 방식의 request를 써야하나요?

3. RESTful한 API를 설계했나요? 어떤 부분이 그런가요? 어떤 부분이 그렇지 않나요?
-네, 적절한 기능 분리를 통해서 Restful 하게 설계 되었다고 생각한다.

4. 적절한 관심사 분리를 적용하였나요? (Controller, Repository, Service)
-네
-서비스는 내부에서 작동하고, 총괄하는 역할을 한다.
-컨트롤러는 외부와의 소통역할을 하고 데이터를 전달받고, 요청을 응답해 주는 역할을 한다.
-레파지토리는 데이터를 넣고 꺼내주는 역할을 한다. 
