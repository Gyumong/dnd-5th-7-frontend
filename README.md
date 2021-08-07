## TIDO 

> 함께해DO, 공유해DO, 모아DO, TIDO :sparkles:

TIDO의 Front-end Repository입니다.

---

### Member

|<img src = "https://user-images.githubusercontent.com/70973495/128445639-6024b415-30d4-4fc8-823f-b1de386edd58.jpg" width="100" height="100"/>|<img src = "https://user-images.githubusercontent.com/70973495/128445744-af2999b6-4f4d-468d-a454-3136834747cc.jpg" width="100" height="100"/>|
|------|---|
|**<div align ="center"><a href="https://github.com/uoayop">김도연</a><div>**|**<div align ="center"><a href="https://github.com/Gyumong">김민규</a><div>**|

</br>
   
### Stack 

<a href="#"><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Vuex-006643?style=flat&logo=V&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Axios-005AF0?style=flat&logo=Academia&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=black"/></a>

### Architecture
![Untitled](https://user-images.githubusercontent.com/70973495/128446091-b7beb3e8-111d-4b16-b5c0-e256b5bc33b1.png)

</br>
   
### Git Branch
- main : 배포 브랜치
- develop : 개발 브랜치
- feature / (기능) : 기능 브랜치 - develop에 merge

   
### Commit Message
<a href="https://gitmoji.dev/">gitmoji</a> 사용 _ [이모지] [코드 설명]

>🎨  ```:art:``` - 기능 구현 <br />
✨  ```:sparkles:``` - 새 기능 <br />
🩹  ```:adhesive_bandage:``` _ 간단한 에러 수정<br />
🚨  ```:rotating_light:``` - 심각한 에러 수정<br />
📝  ```:memo:``` - 문서 업데이트<br />
🔨  ```:hammer:``` - 코딩 컨벤션<br />
>
> 더 추가될 수도 있어요!
   
</br>
   
### Project setup
install
```
npm install
```

Compiles and hot-reloads for development
```
npm run serve
```

Compiles and minifies for production
```
npm run build
```

Lints and fixes files
```
npm run lint
```
</br>

### Directory
```
dnd-5th-7-frontend
├─ README.md
├─ index.html
├─ package.json
└─ src
   ├─ main.js
   ├─ App.vue
   ├─ components        * 컴포넌트 *
   │  ├─ common
   │  └─ ...
   ├─ routes            * 라우터 *
   │  ├─ index.js
   ├─ views             * 라우터 페이지 *
   │  └─ ...
   ├─ store             * 상태 관리 *
   │  ├─ modules
   │  ├─ index.js
   │  └─ ...
   ├─ api               * api 함수 *
   │  └─ ...
   ├─ images            * 이미지 *
   ├─ fonts             * 폰트 *
   └─ assets            * 기타 자원 *
```
