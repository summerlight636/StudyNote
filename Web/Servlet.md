### 2022.08.08
- [Servlet 이란?](https://www.boostcourse.org/web316/lecture/16686?isDesc=false)
- [Servlet 작성 방법-1](https://www.boostcourse.org/web316/lecture/254269?isDesc=false)
- [Servlet 작성 방법-2](https://www.boostcourse.org/web316/lecture/254270/?isDesc=false)
```
web.xml:
3점대 버전(Dynamic Web Version)은 어노테이션 방법을 이용해서 web.xml 파일이 필수는 아니나,
Spring 사용 등 다른 설정 부분을 web.xml에 추가해야할 필요가 있을 수 있다.  

URL mappings:
실제 요청되는 url 상에 해당 서블릿 파일을 요청할 때 어떤 이름으로 요청할 것인지 지정하는 부분 

Servlet:
요청이 들어왔을 때 이 프로그램이 실행되면서 응답할 코드를 만들어내고, 
그때 그 코드로 응답을 하게 하는 것 

클라이언트가 요청을 할 때 서버는 '요청'을 받아내는 객체와 
'응답'을 하기 위한 객체 두 개를 자동으로 만들어낸다. 
요청에 대한 정보들은 이 객체 안에 모두 추상화시켜 가지고 있을 것이다.
```
```Java
setContentType("text/html; charset=utf-8"): //브라우저가 응답을 받았을 때 이런 타입으로 보낼 것이라는 약속을 알려주는 것. 
PrintWriter out = response.getWriter(); 
out.print(<h1>출력내용</h1>);
for(int i = 1; i<=10 ;i++){
	out.println(i+"<br>");
}
out.close();
```

- [Servlet 작성 방법-3](https://www.boostcourse.org/web316/lecture/254271/?isDesc=false)
```2.5 버전에는 어노테이션이 없는대신, web.xml 파일에서 <Servlet>r과 <servlet-mapping> 태그를 확인할 수 있다.``` 
  
- [Servlet 라이프 싸이클-1](https://www.boostcourse.org/web316/lecture/254272?isDesc=false)
- [Servlet 라이프 싸이클-2](https://www.boostcourse.org/web316/lecture/254273?isDesc=false)
- [Request, Response 객체 이해하기-1](https://www.boostcourse.org/web316/lecture/254276?isDesc=false)
- [Request, Response 객체 이해하기-2](https://www.boostcourse.org/web316/lecture/254277/?isDesc=false)
- [Request, Response 객체 이해하기-3](https://www.boostcourse.org/web316/lecture/254278/?isDesc=false)
- [Request, Response 객체 이해하기-4](https://www.boostcourse.org/web316/lecture/254279?isDesc=false)

