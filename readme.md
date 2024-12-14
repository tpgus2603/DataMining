데이터마이닝 프로젝트 
--

RecommendSystem.ipynb파일이 content-based 와 colaborative filtering을 통한 추천시스템코드  user_review, 

TweetCategoryFinal (1).ipynb파일이 사용자 트위터 데이터에 대해 LSH를 적용하여 클러스터링 및 선호 카테고리를 추출한 코드입니다

트위터 크롤링

크롤링 방법 1 ([apidojo/tweet-scraper](https://apify.com/apidojo/tweet-scraper))

1. 회원가입하여 토큰을 발급받고 
2. Input 탭에서 크롤링을 할 타겟 사용자의 도메인을 입력한다. (ex : https://x.com/elonmusk)
3. Start를 누르면 크롤링이 실행된다.
4. Storage 탭에서 export할 데이터 셋의 포멧과 필드를 지정하고 다운로드한다.

크롤링 방법 2 (유료 한정)

1. CrawlingX.ipynb 에서 본인의 api_token을 입력한다.
2. run_input의 "startUrls" 필드에 원하는 URL을 입력한다. (ex : https://x.com/elonmusk)
3. client.actor에 actor ID를 입력하고 실행한다.

