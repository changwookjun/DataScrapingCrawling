Data Scraping 

용어 설명  
* Scraping : 각각의 페이지에서 정보를 추출하는 행위  
* Crawling : 자동으로 정보 추출을 반복하는 프로그램  

Web Site 저작권  
* 저작권 Site 정책 :  url/robots.txt  (예: www.google.com/robots.txt )  
* 한국법 : 2016년 재정된 저작권법 제 30조: 정보 해석을 목적으로 저작물을 복제/번안 가능  

사람처럼 보이기 위한 방법
* 사이트를 너무 빠르게 이동 하지 마세요. (sleep 사용)  
* header를 바꿔서 사용하세요 .  
* 쿠키가 함께 전송 되는지 확인 하세요 .  
* 폼을 전송하거나 POST요청을 보낼 때는 서버에서 기대하는 모든 데이터를 보내세요 . 
  - 크롬 개발자 툴에서 Network Tab을 보면 확인 가능 합니다.
  - 폼의 hidden 필드를 확인 하면 알 수 있습니다. 
* 403 Forbidden Error를 받는다면 IP가 차단 되었을 확률이 높습니다.  
  - 새로운 IP로 요청을 시도 하여야 하므로 가까운 까페에 가서 스크래핑을 수행하세요 ^^  


위에 내용을 모두 만족 하기 위해서 아래와 같이 순차적으로 정리 한 내용 입니다.   


목차  
[01. requests 와 beautifulesoup 을 사용하여 naver news 가져오기](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/01.%20requests%20%20%EC%99%80%20beautifulesoup%20%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC%20naver%20new%20%EA%B0%80%EC%A0%B8%EC%98%A4%EA%B8%B0.ipynb)  

[02. urllib 와 requests을 사용하여 Naver NMT 번역 호출 하기](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/02.%20urllib%20%EC%99%80%20requests%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC%20Naver%20NMT%20%EB%B2%88%EC%97%AD%20%ED%98%B8%EC%B6%9C%20%ED%95%98%EA%B8%B0.ipynb)  

[03. Naver NMT API를 통한 파일 번역](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/03.%20Naver%20NMT%20API%EB%A5%BC%20%ED%86%B5%ED%95%9C%20%ED%8C%8C%EC%9D%BC%20%EB%B2%88%EC%97%AD.ipynb)  

[04.requests를 사용한 네이버 웹툰 이미지 저장하기](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/04.requests%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%9C%20%EB%84%A4%EC%9D%B4%EB%B2%84%20%EC%9B%B9%ED%88%B0%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20%EC%A0%80%EC%9E%A5%ED%95%98%EA%B8%B0.ipynb)  

[05.requests를 이용한 file upload](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/05.requests%EB%A5%BC%20%EC%9D%B4%EC%9A%A9%ED%95%9C%20file%20upload.ipynb) 
[06. beautifulsoup의 parsing하는 여러가지 함수 사용](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/06.%20beautifulsoup%EC%9D%98%20parsing%ED%95%98%EB%8A%94%20%EC%97%AC%EB%9F%AC%EA%B0%80%EC%A7%80%20%ED%95%A8%EC%88%98%20%EC%82%AC%EC%9A%A9.ipynb)  

[07. beautifulsoup의 parsing하는 여러가지 함수 사용 2](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/07.%20beautifulsoup%EC%9D%98%20parsing%ED%95%98%EB%8A%94%20%EC%97%AC%EB%9F%AC%EA%B0%80%EC%A7%80%20%ED%95%A8%EC%88%98%20%EC%82%AC%EC%9A%A9%202.ipynb)  

[08. BeautifulSoup을 사용해서 팟빵 mp3 다운로드 하기](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/08.%20BeautifulSoup%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%B4%EC%84%9C%20%ED%8C%9F%EB%B9%B5%20mp3%20%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20%ED%95%98%EA%B8%B0.ipynb)  

[09.Selenium을 사용한 접근 그리고 로그인 하기](https://github.com/thezili-changwook/DataScrapingCrawling/blob/master/01.%20requests%20%20%EC%99%80%20beautifulesoup%20%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC%20naver%20new%20%EA%B0%80%EC%A0%B8%EC%98%A4%EA%B8%B0.ipynb)  



Author ChangWookJun / @thezili-changwook
