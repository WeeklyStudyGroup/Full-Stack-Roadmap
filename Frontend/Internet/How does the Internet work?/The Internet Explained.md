# The Internet Explained

Source: [The internet, explained](https://www.vox.com/2014/6/16/18076282/the-internet)

## Packet

**패킷**은 인터넷으로 전송되는 기본적인 정보의 단위이다.

패킷은 **헤더**와 **데이터**로 구성된다. **헤더**는 패킷이 목적지(destination)까지 갈 수 있는 도와주는 정보를 가지고 있다. 패킷의 길이, 출발지(source), 목적지, 체크섬 값(checksum value) 등이 헤더에 포함된다. 한 패킷에는 최대 64kb의 데이터를 넣을 수 있다.

인터넷 라우터가 데이터 전송에 문제를 발견한다면 인터넷 라우터는 문제되는 패킷을 버려버린다. 데이터를 송신하는 컴퓨터는 이 패킷이 제대로 보내지지 않았음을 알아낸 뒤 그 패킷을 다시 보내야 한다. 이런 방식이 제일 가성비가 좋다고 한다.

## World Wide Web

WWW은 인터넷에 정보를 퍼블리시하기 위해 가장 많이 쓰이는 방법이다. 웹은 1991년에 CERN에서 일하는 프로그래머 티모시 버너스-리에 의해 만들어졌다. 웹은 다른 인터넷 어플리케이션 보다 강력하고 사용자에게 편리한 인터페이스를 제공했다. 한 번의 클릭으로 다른 문서를 검색할 수 있게 해주는 하이퍼링크 기능을 지원했다.

대기업들이 웹에 어플리케이션을 출시하면서 웹은 정교해져갔다.

버너스-리가 1994년에 웹 공식 표준 단체인 World Wide Web Consortium(W3C)을 만들었다. 하지만 이곳에서 만든 표준은 그렇게 영향력이 크지 않다. 하지만 실제로는 웹 브라우저를 만드는 회사 MS, 구글, 애플, 모질라의 영향력이 더 크다. 개발자들은 이 회사들의 기술을 웹 표준으로 삼고 있다.

인터넷과 동의어로 사용될 정도로 웹은 유명해졌다. 하지만 웹은 인터넷 어플리케이션의 일부일 뿐이다. 인터넷 어플리케이션 중에는 이메일과 빗토렌트 어플리케이션도 있다.

## Web Browser

웹 브라우저는 웹사이트를 다운로드하고 볼 수 있게 해주는 컴퓨터 프로그램이다.

첫번째 브라우저는 **모자이크**다. 모자이크를 만든 일리노이 대학 연구원들은 캘리포니아로 넘어가 **넷스케이프**를 만들었다. 넷스케이프는 1994년에 첫번째로 상업적으로 성공한 웹 브라우저를 만들었다.

넷스케이프의 인기를 이기는 MS의 **인터넷 익스플로러** 등장했다. 넷프케이프의 오픈소스 브라우저는 **파이어폭스**가 되었다. 애플은 2003년에 **사파리**를 출시했다. 구글은 2008년에 **크롬**을 출시했다. 2015년에 크롬은 약 50%의 시장 점유율로 가장 인기 있는 웹 브라우저로 성장했다.

## SSL

Secure Sockets Layer의 약어인 SSL은 웹 사용자가 인터넷으로 전송하는 정보의 프라이버시를 보호해주는 암호화 기술 중 하나다.

SSL이 적용된 사이트에 접속하면 브라우저와 사이트 간의 통신이 암호화된다.

![Screen_Shot_2014-04-08_at_10.55.39_AM.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/37dedd86-1026-4bb0-becc-fb30b249e537/Screen_Shot_2014-04-08_at_10.55.39_AM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220130T131342Z&X-Amz-Expires=86400&X-Amz-Signature=e1dc2807a06ff41778b60e9486f3befe08f2259fa408e613f6d46fd6a474965a&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Screen_Shot_2014-04-08_at_10.55.39_AM.png%22&x-id=GetObject)

브라우저에 자물쇠 모양이 생긴 것을 볼 수 있다. 이 자물쇠는 당신이 보내거나 받는 모든 정보가 암호화됐음을 뜻한다.

SSL이 넷스케이프에 의해 도입된 1994년에는 온라인 뱅킹 같은 특정한 웹사이트에서만 사용됐었다. 하지만 최근에는 SSL을 보편적으로 사용하려고 한다. 2015년에 모질라는 파이어폭스 브라우저의 향후 버전에서 SSL 암호화의 부재를 보안 결함으로 처리한다고 했다. 크롬도 같은 조치를 취한다고 고려한다고 하며 SSL 암호화를 장려하고 있다.

## Domain Name System

웹사이트에 접속하기 위해서는 숫자 아이피 주소를 입력해야 한다. 하지만 숫자 아이피 주소는 외우기 어렵다. 이를 해결하기 위해 DNS(Domain Name System)가 등장했다. DNS는 문자 주소인 도메인 네임을 입력 받아 숫자 아이피 주소로 바꿔준다. 상대적으로 변경하기 힘든 숫자 아이피 주소와 달리 도메인 네임은 사용자가 외우기 편리하게 수정할 수 있다.

이 시스템은 계층적(hierarchical)이다. 예를 들어 `.com` 도메인은Verisign이라는 회사에서 관리한다. Verisign은 `google.com` 및 `vox.com`과 같은 하위 도메인을 할당한다. 이러한 second-level 도메인들은 `mail.google.com`과 `maps.google.com` 과 같은 서브 도메인을 만들 수 있다.

대부분의 사람들은 웹사이트를 도메인 네임을 통해 접속하기 때문에 DNS의 보안이 중요해지고 있다. 암호화로 DNS 보안을 강화하는 DNSSEC라는 표준이 있지만 잘 사용되고 있지 않다.

## **Who decides what domain names exist and who gets them?**

DNS는 캘리포니아에 기반을 둔 비영리조직인 Internet Corporation for Assigned Names and Numbers(ICANN)에서 관리한다. ICANN은 1998년에 설립되었다. 미국 상무부(US Commerce Department)로부터 DNS에 대한 권한을 부여받았지만 미국 정부로부터의 독립성을 점점 더 주장하고 있다.

도메인 네임에는 두 가지가 있다. 첫 번째는 .com, .edu, .org 및 .gov와 같은 일반 최상위 도메인(General Top-Level Domains, gTLD)이다. 인터넷이 미국에서 시작되었기 때문에 이러한 도메인은 미국에서 가장 인기 있다. 이러한 도메인에 대한 권한은 일반적으로 사설 조직에 위임된다.

두 번째는 국가 코드 최상위 도메인(Country-code Top-Level Domains, ccTLD)이다. 세계의 각 국가는 고유한 2자리 코드를 갖는다. 예를 들어, 미국의 ccTLD는 `.us`, 영국의 경우 `.uk`, 중국의 경우 `.cn`이다. 이러한 도메인은 각 국가의 당국에서 관리한다. `.tv`(Tuvalu 섬 국가용) 및 `.io`(영국령 인도양 영토)와 같은 일부 ccTLD는 모국 밖에서 널리 사용되고 있다.

2011년에 ICANN은 새 gTLD를 더 쉽게 생성할 수 있도록 투표했다. 결과적으로 향후 몇 년 안에 수십 또는 수백 개의 새로운 도메인이 생길 수 있다.