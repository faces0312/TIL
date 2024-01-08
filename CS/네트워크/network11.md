# IP 주소 체계 : IPv4와 IPv6

<br>

## IPv4

<br>

![image](https://github.com/faces0312/TIL/assets/112464553/c45579db-36f9-4c51-bb6f-d0aae61a5a82)

<br>

- 부족하기 때문에 NAT, 서브네팅과 같은 부수적인 기술 가능

<br>

- 옥텟이라고 부름

<br>

![image](https://github.com/faces0312/TIL/assets/112464553/667e2383-b6f0-430b-bfd8-a29c8cdeae0f)

<br>

## IPv6

<br>

![image](https://github.com/faces0312/TIL/assets/112464553/86cfc2d9-6f4d-42ca-b39e-cf00ff08aecf)

<br>

- 128비트로 구성, 앞의 64비트는 네트워크, 뒤의 64비트는 인터페이스 주소

<br>

- IPv4보다 빠른 처리 가능, 더 큰 패킷 크기로 인해 일부 사용사례에선 속도가 느려질 수 있음

<br>

- IPv6에는 CRC가 없다(CRC란 체크썸 (데이터가 달라졌는지 확인하는 과정))

<br>

## 클래스풀(Classful IP Addressing)

<br>

- IP 주소는 인터넷 주소로, 네트워크 주소와 호스트 주소로 나뉜다.

<br>

- 네트워크 주소를 매기고 그에 따라 네트워크 크기를 다르게 구분하여 클래스를 할당하는 주소체계

<br>

![image](https://github.com/faces0312/TIL/assets/112464553/101c667f-743e-4df6-bc44-945417e7c724)

<br>

- 문제점

<br>

![image](https://github.com/faces0312/TIL/assets/112464553/fd712e31-cf57-4700-92d4-1135b183b40c)  

<br>

## 클래스리스

- 클래스풀의 단점을 해결하기 위함

<br>

- 클래스를 나누는 것이 아닌 서브넷마스크를 중심으로 나눔

- 용어
  - 서브네팅 : 네트워크를 나눈다
  - 서브넷 : 서브네트워크, 쪼개진 네트워크
  - 서브넷마스크 : 서브네트워크를 위한 비트마스크

<br>

### 서브넷마스크

<br>

- 네트워크주소 부분만 모두 1, 호스트 부분은 0

### 공인IP와 사설IP와 NAT

<br>

- IP주소 부족을 해결하기 위한 방법
  
<br>

- 공인IP(public IP와) 사설IP (Private IP)로 나누고 VAT 기술을 사용

<br>

- 와이파이 공유기를 생각하면 편함

<br>

![image](https://github.com/faces0312/TIL/assets/112464553/e85e66a6-9905-4fc7-9b72-e2a3fe653c1a)