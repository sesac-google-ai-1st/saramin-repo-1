# [사람인](https://www.saramin.co.kr/) 채용공고 크롤링
> [www.saramin.co.kr](www.saramin.co.kr) 사이트에서 검색된 채용 공고의 정보 수집

[![saramin_homepage_img](image.png)](https://www.saramin.co.kr/)


- 검색어를 입력받아서, 채용정보를 수집하기
  - 공고명, 회사명, 등록일, 지원마감일, 근무지역, 경력, 학력, 근무형태, 급여, 직무분야, 링크
- Selenium을 이용하여 크롤링
- 수집된 데이터를 csv 파일로 저장


```bash
# 디렉토리 구조
├── README.md
├── code
│   └── do_crawling.py
└── data
    └── saramin_데이터사이언티스트.csv
``` 

## 설치 방법

1. Selenium 모듈 설치

    ```sh
    pip install selenium
    ```

2. Chrome webdriver 설치

    [Chrome 버전에 맞는 driver 다운로드](https://chromedriver.chromium.org/downloads)
    
    Chrome 버전 확인: `chrome 창 우상단 점 3개 > 도움말 > Chrome 정보`

    압축을 풀고 chrome.exe를 같은 디렉토리에 위치시키기

## 사용 예제

작성 중...