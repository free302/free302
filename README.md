## ๐ Hi, Iโm @free302.
** ์ด ๋ฌธ์์ ์๋ณธ ์ฃผ์๋ [์ฌ๊ธฐ(https://github.com/free302)](https://github.com/free302)์๋๋ค. **

- [x] 2008~2020๊น์ง ๊ดํต์  ์์ ์ ์กฐ ๊ธฐ์์์ ์ฐ๊ตฌ์์ผ๋ก ๊ทผ๋ฌดํ์๋ค.
2012๋ ๋ฌผ๋ฆฌํ๊ณผ [`QuantumOptics`](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99) ์ ๊ณต์ผ๋ก ๋ฐ์ฌํ์๋ฅผ ์ทจ๋ํ์๋ค.
๊ทผ๋ฌดํ ํ์ฌ๋ ๊ดํต์  ์์คํ์ ์ฐ์ด๋ ์ํ ๊ดํ์์์ธ [`WDM์นฉ`](https://ko.wikipedia.org/wiki/%ED%8C%8C%EC%9E%A5_%EB%B6%84%ED%95%A0_%EB%8B%A4%EC%A4%91)๊ณผ ๋ชจ๋์ ๊ฐ๋ฐ ์์ฐํ๋ ํ์ฌ์ด๋ค. 
ํ์ฌ์์ ์ ๋ถR&D๊ณผ์  ๊ธฐํ/๊ด๋ฆฌ, `๊ดํน์ฑ ์ธก์ ์์คํ` ๊ฐ๋ฐ, `์ธก์ ๋ฐ์ดํฐ ๋ถ์SW` ๋ฐ `๋ฐ์ดํฐ๊ด๋ฆฌ Web์๋ฒ` ๊ฐ๋ฐ ๋ฑ์ ์ํํ์๋ค.

- [x] `๊ดํน์ฑ ์ธก์ ์์คํ`์ ์์ฐ๋ WDM ์นฉ์ ๊ดํ์  ํน์ฑ(ํฌ๊ณผ์คํํธ๋ผ)์ ์ธก์ ํ์ฌ ํ์ผ๋ก ์ ์ฅํ๋ค.
์์คํ์ `Mechanical Alignment Part`, `Optical Measurement Part`, `์ ์ดPC`๋ก ๊ตฌ์ฑ๋๋ค.
`MA Part`๋ 50nm ์ ๋ฐ๋์ Motion ์ ์ด๋ถ์ ๊ธฐํ ์ผ์๋ก ๊ตฌ์ฑ๋๋ฉฐ, ์นฉ์ ๊ด์ ๋ฐ ๊ณ์ธก๊ธฐ์ ์ฐ๊ฒฐ๋ ๊ด์ฌ์ ์ ์ ๋ ฌํ๋ค.
`OM Part`๋ ๋น์ ์ธ๊ธฐ๋ฅผ ์ฝ๋ ๊ดํ์๋ฏธํฐ์ ๊ฐ๋ณํ์ฅ์ ๋ ์ด์  ๊ด์(TLS)๋ก ๊ตฌ์ฑ๋๋ฉฐ, ์นฉ์ด ์ ๋ ฌ๋ ์ํ์์ ๊ดํฌ๊ณผ์จ์ ์ธก์ ํ๋ค.
`์ ์ดPC`๋ GPIB/DAQ/USB ๋ฑ์ผ๋ก ๊ฐ ์ฅ์น๋ค์ ์ฐ๊ฒฐ/์ ์ดํ๋ฉฐ `์ธก์ ์ ์ดSW`๋ `C#`์ผ๋ก ๊ฐ๋ฐํ์๋ค.

- [x] ๊ณ ๊ฐ์ธ TLS๋ฅผ ์ฌ๋ฌ ์์คํ์ ๊ณต์ ํ๊ธฐ ์ํด TCP์๋ฒ `TLS Server`๋ฅผ ๊ฐ๋ฐํ์๋ค.
์๋ฒ์ ํด๋ผ์ด์ธํธ์ ์ฅ์น๋ค์ ์ ๊ธฐ์ /๊ดํ์ ์ผ๋ก ์ฐ๊ฒฐ๋๋ฉฐ ์ ์ดPC๋ TCP ์์ผ์ผ๋ก ์ฐ๊ฒฐ๋๋ค.
1๊ฐ์ TLS๋ฅผ 2๊ฐ์ ํด๋ผ์ด์ธํธ ์์คํ์ด ์ฌ์ฉ์ ์ฝ๊ฐ์ ์ฑ๋ฅ์ ํ(์ธก์ ์๊ฐ์ฆ๊ฐ)๊ฐ ์์ง๋ง, ์ดํ 6๊ฐ๊น์ง ํด๋ผ์ด์ธํธ๋ฅผ ๋๋ ค๋ ์ถ๊ฐ ์ฑ๋ฅ์ ํ๋ ์์์ผ๋ฉฐ, ์๋ฎฌ๋ ์ด์ ๊ฒฐ๊ณผ ์์ญ๊ฐ์ ํด๋ผ์ด์ธํธ์ ์ฐ๊ฒฐ๋ํด ์ถ๊ฐ ์ฑ๋ฅ์ ํ๋ ๋ํ๋์ง ์์๋ค.

- [x] ํ์ฒญ์์ฒด์ ์ ๊ณตํ๋ `์ธก์ SW`์ ๋ํ์ฌ 2๊ฐ์ง ํด์ ๊ฐ๋ฐํ์ฌ ๋ถ์ ์ ํ ์ฌ์ฉ์ ๋ฐฉ์งํ์๋ค.
`native wrapping tool`์ `C++`๋ก ์์ฑ๋ native binary๋ก ๋ชจ๋  `C# exe & dll`๋ฅผ ๋ํํ์ฌ IL decompile์ ๋ฐฉ์งํ๋ค.
๋ํ `license tool`์ ์ ์ดPC ๊ณ ์ ์ ์ ๋ณด๋ฅผ ์ธ์ํ์ฌ `์ธก์ SW`์ ๋ฌด๋จ๋ณต์ฌ ์ฌ์ฉ์ ๋ฐฉ์งํ๋ค.

- [x] ์ธก์ ๋ ํฌ๊ณผ์คํํธ๋ผ์ ๋ถ์ํ๊ธฐ ์ํ `wdm analyzing library`๋ฅผ ๊ฐ๋ฐํ์ฌ ๋ฐ์คํฌํ ์ฑ๊ณผ ์น์๋ฒ์ ์ฌ์ฉํ์๋ค(c# & phthon).
๋ผ์ด๋ธ๋ฌ๋ ์ฝ๋์์  ์์ด ์ฌ๋ฌ ๋ถ์์๊ณ ๋ฆฌ์ฆ์ ๋์ํ๋๋ก ์ ์ฐํ๊ฒ ์ค๊ณํ์๊ณ  ์๋ง๊ฐ์ ํ์ผ์ ์ฒ๋ฆฌํ๋๋ฐ ๋ณ๋ น์ฒ๋ฆฌ ๊ธฐ๋ฒ์ ์ฌ์ฉํ๋ค.

- [x] `๋ฐ์ดํฐ๊ด๋ฆฌ Web์๋ฒ`๋ ์ด๊ธฐ๋ฒ์ ์ python๊ณผ Django๊ธฐ๋ฐ์ผ๋ก ๊ฐ๋ฐํ์์ผ๋ฉฐ, ์ดํ `PostgreSQL` DB์๋ฒ์ asp.net์ผ๋ก ์ฌ๊ฐ๋ฐํ์๋ค.
๋ฐฑ์๋์ ํ๋ฆฐํฐ์๋ ๋ชจ๋์ C#์ด ์ฌ์ฉ๊ฐ๋ฅํ [`Blazor`](https://docs.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-5.0) ๊ธฐ์ ์ ํ์ฉํ๊ณ ,
์ถํ ์ถ๊ฐ๋๋ ๋ฐ์ดํฐ๋ชจ๋ธ์ ๊ธฐ์กด์ฝ๋ ์์ ์์ด ๋ฐํ์์ ์์ฑํ  ์ ์๋๋ก `OpCode Emission`๊ธฐ๋ฒ์ผ๋ก `Dynamic DB Context`๋ฅผ ๊ฐ๋ฐํ์๋ค.

- [x] ๊ทธ ์ธ ๊ด์ ๋ณํ์ฅ์น(optical powermeter), ํธ๊ด์ ์ด์ฅ์น(polarization controller) ๋ฑ HW์ฅ๋น์ firmware๋ฅผ ๊ฐ๋ฐํ์๋ค.

#### ๋ค๋ฃจ๋ ์ธ์ด์ ํด:
- [x] ์ฌ์ฉ์ธ์ด: C#, C/C++, Python, Java, Mathematica, Javascript, [`TeX`](https://ko.wikipedia.org/wiki/TeX)
- [x] TOOLs: Mathematica, Visual Studio, Notepad++, Git/Github, 3D Inventor, Altium Designer(์ ์ํ๋ก์ค๊ณ), C2V Olympios(๊ด๋ํ๋ก์ค๊ณ), Avr Studio

#### Getting in touch:
- [x] [:e-mail:](mailto:amadeus.bae@gmail.com) *amadeus.bae@gmail.com* [:phone: *010-9066-3569*](tel:010-9066-3569) [Slack](https://universesoft.slack.com/)

## :card_file_box: My Repositories
๊ด๋ฆฌ๋ฅผ ์ํด ๋๋๋ก ์ฑ(UI)๊ณผ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ ๋ถ๋ฆฌํ์๋ค.

#### ์ต๊ทผ ๊ด์ฌ๋ถ์ผ/์งํ์ค ํ๋ก์ ํธ (C#/Python)
- [x] ์ค๋งํธํ ์ผ์ ๋ฐ์ดํฐ ๊ด๋ฆฌ (Python/Flask/Dash) [`cams-server`](https://github.com/free302-b2f/cams-server)
- [x] Spectrometer Measure & Analysis by Machine Learning [`ML`](https://github.com/free302/FiraAiSpecML) [`UI`](https://github.com/free302/FiraAiSpec)
 - ์คํํธ๋ผ ๋ถ์์ ํตํ ๋น์ฑํ ํ๋น์ธก์ ๊ธฐ ์ด์ฉ์ฑ ๋ฐ ML ๋ถ์ ๋ผ์ด๋ธ๋ฌ๋ฆฌ([`ML.NET`](https://docs.microsoft.com/ko-kr/dotnet/machine-learning/))
- [x] Coin Trading System [`UpbitTrader`](https://github.com/free302-BC/UpbitTrader)
 - Crypto-Currency ์๋๊ฑฐ๋ ์์คํ, ์๊ณ ๋ฆฌ์ฆ ํ๋ฆฌ๋ฏธํฐ ์ปจํธ๋กค

#### Library Projects (C#)
- [x] TLS ๊ณต์ ๋ฅผ ์ํ [`UniverseTcp`](https://github.com/free302/UniverseTcp)
 - TCP server/client library, TLS ์ ์ด ๋ฐ ํต์ ๋ฐ์ดํฐ ๋ถ์
- [x] ์ธก์ ๋ฐ์ดํฐ ๋ถ์์ ์ํ [`UniverseWdm`](https://github.com/free302/UniverseWdm)
 - ๊ณตํต interface/์๋ฃํ, ๋ฐ์ดํฐ (ํฌ๊ณผ์คํํธ๋ผ) ๋ถ์ ๊ตฌํ
- [x] Web application์ ์ํ [`WebData`](https://github.com/free302/WebData)
 - Generic model interface, dynamic db context interface & implimentation
- [x] ๊ฐ์ข ์ ํธ๋ฆฌํฐ ํด๋์ค ๋ชจ์ [`UniverseUtility`](https://github.com/free302/UniverseUtility)
 - Reflection์ ์ด์ฉํ ์ค์ ํ์ผ๊ด๋ฆฌ, ์ค์ ํ์ผ๋ด ๋ฌธ์์ด ์กฐ์&Casting ๋ฑ ๋ฌธ์์ด ํ์ฅ
 - ๋ค์คํค Dictionary/ํด์ฌ์ฝ๋ ๋ฑ ์๋ฃ๊ตฌ์กฐ, ์์ถ, native/.net ๋ก๋ ๋ฑ
- [x] VS ํ๋ก์ ํธ ๋ฒ์ ์ ์๋์ผ๋ก ์ค์ ํด์ฃผ๋ ํ๋ฌ๊ทธ์ธ [`BuildVersion`](https://github.com/free302/BuildVersion)
 - major.minor๋ ์๋์กฐ์, build.revision์ utc 2000-1-1T00:00:00 ๊ธฐ์ค์ผ๋ก ๋น๋์๊ฐ์ ์ผ์(days)์ 2์ด๋จ์๋ก ์ค์ 

#### Protection Tools (C#/C++)
- [x] ๋์ปดํ์ผ ๋ฐฉ์ง native wrapping tool  [`CppWrap`](https://github.com/free302/CppWrap) (C++)
- [x] ๋ณต์ฌ ๋ฐฉ์ง ํด [`UniverseLicense`](https://github.com/free302/UniverseLicense)

#### ๊ดํน์ฑ ์ธก์ ์์คํ ์ด์ฉ ๊ด๋ จ ์ฑ ๋ฐ ์น์๋ฒ
- [x] ๋ฐ์ดํฐ ๋ถ์/๊ด๋ฆฌ Web Application [`WdmServer`](https://github.com/drbae/WdmServer) (ASP.NET Core)
- [x] ๊ดํน์ฑ ์ธก์ ์์คํ์ ์๋ฒ ์ฑ [`TlsServer`](https://github.com/drbae/TlsServer)
- [x] ๊ดํน์ฑ ์ธก์ ์์คํ์ ํด๋ผ์ด์ธํธ ์ฑ [`OdmsSw`](https://github.com/drbae/OdmsSw)
- [x] ๊ดํน์ฑ ์ธก์ ์์คํ์ ๋ฐ์ดํฐ๋ถ์ ์ฑ [`WdmAnalyzer`](https://github.com/drbae/WdmAnalyzer)
- [x] WDM๋ชจ๋ ์ธก์ ์ฉ ์ฑ [`Pigtail`](https://github.com/drbae/Pigtail)
- [x] `๊ดํน์ฑ ์ธก์ ์์คํ`์ ์ฌ์์ [`SpecSheet`](https://github.com/free302/SpecSheet) (Tex)

#### ๊ธฐํ ์ก๋คํ ๊ฒ๋ค
- [x] NavyField ๊ฒ์ ์๋ณ๋ฝ๊ธฐ ์๋ํ ํด [`NFTool`](https://github.com/free302/NFTool)
- [x] 21๋ ์ด์  ์ค์ฐ๋์  ๊ตญํ์์์ ๊ณ์ฐ๊ธฐ [`Congress`](https://github.com/free302/Congress)
- [x] NTFS ํ์ผ์ alternate stream lib [`NtfsAltStream`](https://github.com/free302/NtfsAltStream)
- [x] ์ฌ์ ๋ ๋ฐ์ดํฐ์์ ์ค์๊ฐ ์ฌ๋ฐ์ ๊ณ์ฐ ๋ฐ ์๊ฐํ ์ฑ [`EcgDev`](https://github.com/free302/EcgDev)
- [ ] *๊ธํ์ ์กฐ์์ฒด์ ๊ธํ๊ด๋ฆฌ ์น์๋ฒ (C# app์ activex๋ก ๋ณํ)*
- [ ] *Android ์ฉ ์ฐ๋ฝ์ฒ ๊ด๋ฆฌ, SMS ๋ฐ์ก ์ฑ (Java)*
- [ ] *๋ง์ฐ์ค ๋งคํฌ๋ก๋ฅผ ์ํ ๊ฐ์ ๋ง์ฐ์ค ๋๋ผ์ด๋ฒ (C++)*

<!---
free302/free302 is a โจ special โจ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
