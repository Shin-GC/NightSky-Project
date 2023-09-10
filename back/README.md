# BACK README

---

> ---
>
> ### 사용 라이브러리
>
> - **Sentry** : 에러 관리 모니터링
> - **morgan** : Request 요청 로그 확인
> - **cors** : CORS 방지 미들웨어
> - **Swagger** : API 문서화
> - **compression** : Gzip 압축을 이용하여 웹 앱 속도 향상을 위한 미들웨어
> - **dotenv** : 환경 변수 읽어오기
>
> ---

---

> ---
>
> ### 폴더 구조
>
> 📦src  
> ┣ 📂config  
> ┃ ┣ 📜env.js  
> ┃ ┗ 📜swaggerDoc.js  
> ┣ 📂db  
> ┃ ┣ 📂models  
> ┃ ┣ 📂schemas  
> ┃ ┗ 📜index.js  
> ┣ 📂middlewares  
> ┣ 📂routers  
> ┃ ┗ 📜basicRouter.js  
> ┣ 📂services  
> ┃ ┗ 📜basicService.js  
> ┣ 📂test  
> ┃ ┗ 📜test.js  
> ┗ 📜app.js  
>
> ---
>
> - **config** : 설정 파일을 모아두는 폴더
> - **models** : DB 모델 파일
> - **schemas** : Schema 구성 파일
> - **middlewares** : 미들웨어 구성 파일을 모아두는 폴더
> - **routers** : Router 구성 파일을 모아두는 폴더
> - **services** : Service 비지니스 로직을 작성한 파일을 모아두는 폴더
> - **test** : test 코드를 작성한 파일을 모아두는 폴더
>
> ---
