## 👋 Hi, I’m @free302.
- [x] 2008~2020까지 중소기업 연구소에서 연구개발자로 근무하였다.
2012년 물리학과 [양자광학](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99) 전공으로 박사학위를 취득하였다.
근무한 회사는 광통신 시스템에 쓰이는 소형 광학소자인 [`WDM칩`](https://ko.wikipedia.org/wiki/%ED%8C%8C%EC%9E%A5_%EB%B6%84%ED%95%A0_%EB%8B%A4%EC%A4%91)과 모듈을 개발 생산하는 회사이다. 
회사에서 정부R&D과제 기획/관리, `광특성 측정시스템` 개발, `측정데이터 분석SW` 및 `데이터관리 Web서버` 개발 등을 수행하였다.

- [x] `광특성 측정시스템`은 생산되 WDM 칩의 광학적 특성(투과스펙트럼)을 측정하여 파일로 저장한다.
시스템은 `Mechanical Alignment Part`, `Optical Measurement Part`, `제어PC`로 구성된다.
`MA Part`는 50nm 정밀도의 Motion 제어부와 기타 센서로 구성되며, 칩을 광원 및 계측기에 연결된 광섬유와 정렬한다.
`OM Part`는 빛의 세기를 읽는 광파워미터와 가변파장의 레이저 광원(TLS)로 구성되며, 칩이 정렬된 상태에서 광투과율을 측정한다.
`제어PC`는 GPIB/DAQ/USB 등으로 각 장치들을 연결/제어하며 `측정제어SW`는 `C#`으로 개발하였다.

- [x] 고가인 TLS를 여러 시스템에 공유하기 위해 TCP서버 `TLS Server`를 개발하였다.
서버와 클라이언트의 장치들은 전기적/광학적으로 연결되며 제어PC는 TCP 소켓으로 연결된다.
1개의 TLS를 2개의 클라이언트 시스템이 사용시 약간의 성능저하(측정시간증가)가 있지만, 이후 6개까지 클라이언트를 늘려도 추가 성능저하는 없었으며, 시뮬레이션 결과 수십개의 클라이언트와 연결도해 추가 성능저하는 나타나지 않았다.

- [x] 하청업체에 제공하는 `측정SW`에 대하여 2가지 툴을 개발하여 부적절한 사용을 방지하였다.
`native wrapping tool`은 `C++`로 작성된 native binary로 모든 `C# exe & dll`를 래핑하여 IL decompile을 방지한다.
또한 `license tool`은 제어PC 고유의 정보를 인식하여 `측정SW`의 무단복사 사용을 방지한다.

- [x] 측정된 투과스펙트럼을 분석하기 위한 `wdm analyzing library`를 개발하여 데스크탑 앱과 웹서버에 사용하였다(c# & phthon).
라이브러는 코드수정 없이 여러 분석알고리즘에 대응하도록 유연하게 설계하였고 수만개의 파일을 처리하는데 병령처리 기법을 사용한다.

- [x] `데이터관리 Web서버`는 초기버전은 python과 Django기반으로 개발하였으며, 이후 `PostgreSQL` DB서버와 asp.net으로 재개발하였다.
백엔드와 프린터엔드 모두에 C#을 사용가능한 `Blazor` 기술을 활용하고,
추후 추가되는 데이터모델을 기존코드 수정없이 런타임에 생성할 수 있도록 `OpCode Emission`기법으로 `Dynamic DB Context`를 개발하였다.

- [x] 그 외 광전변환장치(optical powermeter), 편광제어장치(polarization controller) 등 HW장비와 firmware를 개발하였다.

#### 다루는 언어와 툴:
- [x] 사용언어: C#, C/C++, Python, Java, Mathematica, Tex, Javascript
- [x] TOOLs: Mathematica, Visual Studio, Notepad++, Git/Github, 3D Inventor, Altium Designer(전자회로설계), C2V Olympios(광도파로설계), Avr Studio

#### Getting in touch:
- [x] [:e-mail:](mailto:samyong.bae@gmail.com) *samyong.bae@gmail.com* [:phone: *010-9066-3569*](tel:010-9066-3569)

## :card_file_box: My Repositories
관리를 위해 되도록 앱(UI)과 라이브러리를 분리하였다.

#### Library Projects (C#)
- [x] TLS 공유를 위한 `TcpServer`
 - TCP server/client library, TLS 제어 및 통신데이터 분석
- [x] 측정데이터 분석을 위한 `WdmDataAnalysis`
 - 공통 interface/자료형, 데이터 (투과스펙트럼) 분석 구현
- [x] 각종 유틸리티 클래스 모음
 - Reflection을 이용한 설정파일관리, 설정파일내 문자열 조작&Casting 등 문자열 확장
 - 다중키 Dictionary/해쉬코드 등 자료구조, 압축, native/.net 로더 등
- [x] VS 프로젝트 버전을 자동으로 설정해주는 플러그인 [`BuildVersion`](https://github.com/free302/BuildVersion)
 - major.minor는 수동조작, build.revision을 utc 2000-1-1T00:00:00 기준으로 빌드시각의 일수(days)와 2초단위로 설정
- [x] Web application을 위한 [`WebData`](https://github.com/drbae/WebData)
 - Generic model interface, dynamic db context interface & implimentation

#### Protection Tools (C#/C++)
- [x] 디컴파일 방지 `native wrapping tool`
- [x] 복사 방지 `license tool`

#### 광특성 측정시스템의 `측정제어SW` 및 웹서버
- [x] 데이터 분석/관리 Web Application [`WdmServer`](https://github.com/drbae/WdmServer) (ASP.NET Core)
- [x] 광특성 측정시스템의 `TLS Server`
- [x] 측정시스템의 `데이터분석SW`
- [x] WDM모듈 측정용 앱 `Pigtail`

#### 기타 잡다한 것들
- [x] NavyField 게임 수병뽑기 자동화 툴 (C#)
- [x] 21대 총선 준연동제 국회의석수 계산기 (C#)
- [x] NTFS 파일의 `extra stream` read/write lib (C#)
- [x] 심전도 데이터에서 실시간 심박수 계산 및 시각화 앱 (C#)
- [x] Android 용 연락처 관리, SMS 발송 앱 (Java)
- [ ] *마우스 매크로를 위한 가상 마우스 드라이버 (C++)*

<!---
free302/free302 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
