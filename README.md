### 👋 Hi, I’m @free302.
- [x] 2008~2020까지 중소기업 연구소에서 연구개발자로 근무하였다.
2012년 물리학과 [양자광학](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99) 전공으로 박사학위를 취득하였다.
근무한 회사는 광통신 시스템에 쓰이는 소형 광학소자인 [`WDM칩`](https://ko.wikipedia.org/wiki/%ED%8C%8C%EC%9E%A5_%EB%B6%84%ED%95%A0_%EB%8B%A4%EC%A4%91)과 모듈을 개발 생산하는 회사이다. 
회사에서 정부R&D과제 기획/관리, `광특성 측정시스템` 개발, `측정데이터 분석SW` 및 `데이터관리 Web서버` 개발 등을 수행하였다.

- [x] `광특성 측정시스템`은 생산되 WDM 칩의 광학적 특성(투과스펙트럼)을 측정하여 파일로 저장한다.
시스템은 칩을 광원 및 계측기에 연결된 광섬유와 정렬하는 `Mechanical Alignment Part`, 광투과율을 측정하는 `Optical Measurement Part`, 이들을 모두 제어하는 `제어PC`로 구성된다.
`MA Part`는 50nm 정밀도의 Motion 제어부와 기타 센서로 구성되며,
`OM Part`는 빛의 세기를 읽는 광파워미터와 가변파장의 레이저 광원(TLS)로 구성된다.
`제어PC`와 각 장치들은 GPIB/DAQ/USB 등으로 연결되며, `측정제어SW`는 `C#`으로 개발하였다.

- [x] 고가인 TLS를 여러 시스템에 공유하기 위해 TCP 서버를 개발하였다.
서버와 클라이언트의 장치들은 전기적/광학적으로 연결되며 제어PC는 TCP 소켓으로 연결된다.
1개의 TLS를 2개의 클라이언트 시스템이 사용시 약간의 성능저하(측정시간증가)가 있지만, 이후 6개까지 클라이언트를 늘려도 추가 성능저하는 없었다.

- [x] 하청업체에 제공하는 `측정SW`에 대하여 2가징 툴을 개발하여 부적절한 사용을 방지하였다.
`native wrapping tool`은 `C++`로 작성된 native binary로 모든 `C# exe & dll`를 래핑하여 bytecode decompile을 방지한다.
또한 `license tool`은 제어PC 고유의 정보를 인식하여 `측정SW`의 무단복사 사용을 방지한다.

- [ ] 측정된 투과스펙트럼을 분석하기위한 `wdm analyzing library`를 개발하여 데스크탑 앱과 웹서버에 사용하였다(c# & phthon).
`wdm analyzing library`는 분석알고리즘 선택이 가능하도록 유연하게 설계하였고 수만개의 파일을 처리하는데 병령처리 기법을 사용한다.

- [ ] `데이터관리 Web서버`는 `PostgreSQL` DB서버와 asp.net 기반이며 백엔드와 프린터엔드 모두에 C#을 사용가능한 `Blazor` 기술을 활용하고,
추후 추가되는 데이터모델을 기존 코드 수정없이 런타임에 생성할 수 있도록 `Dynamic DB Context` 기법을 이용한다.

- [x] I got a __Ph.D__ in physics ([quantum optics](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99) experiment) in 2012.
- [x] These days I’m interested in 2 years old baby and in `machine learning`.

#### Getting in touch:
[:e-mail:](mailto:samyong.bae@gmail.com) *samyong.bae@gmail.com* [:phone: *010-9066-3569*](tel:010-9066-3569)

### My Repositories
#### Test & Measurement System Using TCP Server/Client (C#)
#### Web App Using Dynamic DB Models (C# & ASP.NET)
#### Utility Projects  (C# & C++)


<!---
free302/free302 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
