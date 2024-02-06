# 손정민 이력서 페이지

## 내용 수정할 때

- 노션 export -> HTML

  - 이미지 포함

- 파일 수정하기

  - 아래 설정 그대로 `index.html` 파일 거의 제일 밑에 붙여넣기

    ```js
    /*** 현호 수정 시작 ***/
    /* 최대 폭 조절 */
    @media only screen {
        body {
            margin: 2em auto;
            max-width: 700px; /* 👈 */
            color: rgb(55, 53, 47);
        }
    }

    /* 연락처 부분 폰트 줄임 */
    blockquote {
        font-size: 1em; /* 👈 */
        margin: 1em 0;
        padding-left: 1em;
        border-left: 3px solid rgb(55, 53, 47);
    }

    /* 사진 왼쪽 정렬, 마진 제거 */
    .image {
        border: none;
        margin: 0; /* 👈 */
        padding: 0;
        border-radius: 0;
        text-align: left; /* 👈 */
    }

    /* 코드블럭 폰트 늘림 */
    .code,
    code {
        background: rgba(135, 131, 120, 0.15);
        border-radius: 3px;
        padding: 0.2em 0.4em;
        border-radius: 3px;
        font-size: 100%; /* 👈 */
        tab-size: 2;
    }

    /* 이미지 크기 줄이기 */
    /* `style="width:288px"` -> `style="width:240px"` */

    /* 우아한 형제들 밑에 br 지우기 */
    /* `</mark>피플실, 온보딩팀</h2>` 앞에 있는 <br/> 블럭 1개 지우기 */

    /* 사진 위에 빈 공간 지우기 */
    /* `<strong>총 2년 0개월)</strong></mark></p>` 뒤에 있는 <p> 블럭, 다음 줄에 <p/> 블럭 2개 지우기 */

    /* 사진 닫히게 설정 (모두 바꾸기) */
    /* ` open=""` -> `` */

    /* 이미지 경로 수정 (모두 바꾸기)) */
    /* `%E1%84%92%E1%85%A2%E1%86%BC%E1%84%87%E1%85%A9%E1%86%A8%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%80%E1%85%A7%E1%86%AB%E1%84%80%E1%85%A1,%20%E1%84%89%E1%85%A9%E1%86%AB%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%86%E1%85%B5%E1%86%AB%20(%E1%84%92%E1%85%A7%E1%84%82%E1%85%A9%E1%84%87%E1%85%A5%E1%84%8C%E1%85%A5%E1%86%AB)%202f1b30dcff7b427f8c6f9efebaf50df6` -> `assets` */

    /*** 현호 수정 끝 ***/

    ```

  - 수동으로 블럭 지우기
  - 수동으로 바꾸기

## 아이콘 수정할 때

- [favico 생성](https://realfavicongenerator.net/)
  - theme 색: #E6D2DC

## 도메인 관련

- [가비아](https://www.gabia.com/)에서 도메인 구입
  - [가이드](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) 참고해 도메인 IP 할당
