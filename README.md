# 주요 개발 환경
```
react: 17.0.1
create-react-app: 4.0.1
redux: 4.0.5 
redux-saga: 1.1.3
mongoDB: 4.4.3
yarn 1.22.10
```
# 프로젝트 설명
```
게시판 프로젝트
리엑트를 사용,리덕스를 통한 상태 관리
```
# 폴더 구조
```
blog
│  
├─blog-backend
│  │  .env
│  │  .eslintrc.json
│  │  .prettierrc
│  │  jsconfig.json
│  │  
│  └─src
│      │  index.js
│      │  main.js
│      │  
│      ├─api
│      │  │  index.js
│      │  │  
│      │  ├─auth
│      │  │      auth.ctrl.js
│      │  │      index.js
│      │  │      
│      │  └─posts
│      │          index.js
│      │          posts.ctrl.js
│      │          
│      ├─lib
│      │      checkLoggedIn.js
│      │      jwtMiddleware.js
│      │      
│      └─models
│              post.js
│              user.js
│              
└─blog-frontend
    │  .eslintcache
    │  .gitignore
    │  .prettierrc
    │  jsconfig.json
    │  yarn.lock
    │  
    └─src
        │  App.css
        │  App.js
        │  App.test.js
        │  index.css
        │  index.js
        │  logo.svg
        │  reportWebVitals.js
        │  setupTests.js
        │  
        ├─components
        │  ├─auth
        │  │      AuthForm.js
        │  │      AuthTemplate.js
        │  │      
        │  ├─common
        │  │      AskModal.js
        │  │      Button.js
        │  │      Header.js
        │  │      Responsive.js
        │  │      SubInfo.js
        │  │      Tags.js
        │  │      
        │  ├─post
        │  │      AskRemoveModal.js
        │  │      PostActionButtons.js
        │  │      PostViewer.js
        │  │      
        │  ├─posts
        │  │      Pagination.js
        │  │      PostList.js
        │  │      
        │  └─write
        │          Editor.js
        │          TagBox.js
        │          WriteActionButtons.js
        │          
        ├─containers
        │  ├─auth
        │  │      LoginForm.js
        │  │      RegisterForm.js
        │  │      
        │  ├─common
        │  │      HeaderContainer.js
        │  │      
        │  ├─post
        │  │      PostViewerContainer.js
        │  │      
        │  ├─posts
        │  │      PaginationContainer.js
        │  │      PostListContainer.js
        │  │      
        │  └─write
        │          EditorContainer.js
        │          TagBoxContainer.js
        │          WriteActionButtonsContainer.js
        │          
        ├─lib
        │  │  createRequestSaga.js
        │  │  
        │  ├─api
        │  │      auth.js
        │  │      client.js
        │  │      posts.js
        │  │      
        │  └─styles
        │          palette.js
        │          
        ├─modules
        │      auth.js
        │      index.js
        │      loading.js
        │      post.js
        │      posts.js
        │      user.js
        │      write.js
        │      
        └─pages
                LoginPages.js
                PostListPage.js
                PostPage.js
                RegisterPage.js
                WritePage.js
                
```

# 프로젝트 실행 yarn start
```
blog-backend폴더에서 명령어로 local:4000으로 디비 사용가능
blog-frontend폴더에서 명령어를 실행하여 local:3000에 접속 가능
이후 프로젝트 실행
```
