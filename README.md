# 환경세팅

## venv 세팅

```shell
> python3.8 -m venv venv
```

또는  

```shell
> python -m venv venv
```

## venv 활성화 

### 윈도우10  

```shell
> venv\\Scripts\activate.bat
```

### 리눅스/맥

```shell
> ./venv/Scripts/activate
```

### 모듈 설치

- 반드시 venv 실행된 상태에서 진행해야함.
  
```shell
(venv)> pip install requests
```

---

## 날씨 정보 조회 서비스

- 참조 URL <https://www.data.go.kr/iim/api/selectAPIAcountView.do>
- 위 사이트에서 제공하는 doc 문서 상세히 읽어봐야 함.

### 메인 모듈

```shell
> python3 open_weather.py
```
  
### 동네예보 주요 코드

![1](weather_code.png)

### 동네예보 base_time 안내

![2](weather_time.png)
  
### 동네예보 가이드 문서 전체 보기

![p1](./docs/api_guide_01.jpg)
![p2](./docs/api_guide_02.jpg)
![p2](./docs/api_guide_03.jpg)
![p2](./docs/api_guide_04.jpg)
![p2](./docs/api_guide_05.jpg)
![p2](./docs/api_guide_06.jpg)
![p2](./docs/api_guide_07.jpg)
![p2](./docs/api_guide_08.jpg)
![p2](./docs/api_guide_09.jpg)
![p2](./docs/api_guide_10.jpg)
![p2](./docs/api_guide_11.jpg)
![p2](./docs/api_guide_12.jpg)
![p2](./docs/api_guide_13.jpg)
![p2](./docs/api_guide_14.jpg)
![p2](./docs/api_guide_15.jpg)
![p2](./docs/api_guide_16.jpg)
![p2](./docs/api_guide_17.jpg)
![p2](./docs/api_guide_18.jpg)
![p2](./docs/api_guide_19.jpg)
![p2](./docs/api_guide_20.jpg)
![p2](./docs/api_guide_21.jpg)
![p2](./docs/api_guide_22.jpg)
![p2](./docs/api_guide_23.jpg)
![p2](./docs/api_guide_24.jpg)
![p2](./docs/api_guide_25.jpg)
![p2](./docs/api_guide_26.jpg)
![p2](./docs/api_guide_27.jpg)
![p2](./docs/api_guide_28.jpg)
![p2](./docs/api_guide_29.jpg)
![p2](./docs/api_guide_30.jpg)
![p2](./docs/api_guide_31.jpg)
