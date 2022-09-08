## proxy & Loadbalancer

* Proxy Server
> In computer networking, a proxy server is a server application that acts as an intermediary between a client requesting a resource and the server providing that resource. Instead of connecting directly to a server that can fulfill a request for a resource, such as a file or web page, the client directs the request to the proxy server, which evaluates the request and performs the required network transactions. This serves as a method to simplify or control the complexity of the request, or provide additional benefits such as load balancing, privacy, or security. Proxies were devised to add structure and encapsulation to distributed systems. A proxy server thus functions on behalf of the client when requesting service, potentially masking the true origin of the request to the resource server.

### Proxy Server
![img](https://miro.medium.com/max/700/1*2LmccMiuHiqxbP8vQiq-Mg.png)
- 클라이언트 사이드를 보호함, Client의 IP가 안보인다.

### Reverse Proxy Server
![img](https://miro.medium.com/max/700/1*NmjDpizyxCCyHHF2nNmqDg.png)
- 서버 사이드를 보호함, Server의 IP가 안보임
- 어떤 서버에 접속했는지 모름
- 정적/동적 컨텐츠를 캐시할 수 있어, 굳이 뒤의 서버로 통신할 필요 없음
- Loadbalancer 역할도 할 수 있음

### Loadbalancer
![img](https://miro.medium.com/max/700/1*qxL2lfG-pg3iKG3GQGHS-w.png)
- 모든 리버스 프록시는 LB로 동작하지는 않지만, 모든 LB는 리버스 프록시로 동작함
- 

* 결론 : 프록시 기능을 통해 캐싱, 리버스 프록싱, 로드밸런싱을 할 수 있고 이는 네트워크와 보안, 성능에 


## 참고
refer : https://medium.com/tech-it-out/proxy-vs-reverse-proxy-vs-load-balancer-3937915631c8
