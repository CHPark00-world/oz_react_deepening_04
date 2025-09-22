<<<<<<< HEAD
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
=======
- **주제 : `map` 메서드와 `filter` 메서드를 이용해 props를 넘겨 화면 렌더링하기**
- 학습 목표
    1. 2일차에서 배운 map, filter를 이용한 **데이터 가공**을 컴포넌트 단위로 이해한다.
    2. Props의 사용법에 대해 이해한다.
    
- 복습할 개념 체크 리스트
    - [ ]  **React가 데이터를 관리하는 방식**
    설명: React가 데이터를 관리하는 방식에 대해 복습하세요.
    - [ ]  **Props의 개념과 사용하는 방법**
    설명: Props의 개념과 사용하는 방법에 대해 복습하세요.
    - [ ]  **React에서 map으로 컴포넌트를 렌더링 하는 방법**
    설명: `map()` 메서드를 사용해 데이터를 순회하는 방법에 대해 복습하세요.
    - [ ]  **React에서 filter로 컴포넌트를 필터링 하는 방법**
    설명: `filter()` 메서드를 사용해 데이터 필터링에 대해 복습하세요.
<hr/>

- **문제 요구 사항**

- `CardList.jsx` 컴포넌트 내 요구 사항
    - 카드의 리스트 UI를 담당하는 컴포넌트 입니다.
    - `listData`를 받아와서 카드 리스트를 렌더링 해야 합니다.
    - `listData`의 각 요소를 `Card.jsx` 컴포넌트에 props로 넘겨주어야 합니다.
    - `Card.jsx` 컴포넌트에는 `item`을 넘겨주어야 합니다.
    
- `Card.jsx` 컴포넌트 내 요구사항
    - 카드의 1개의 UI를 담당하는 컴포넌트 입니다.
    - `item`을 받아와서 카드를 렌더링 해야 합니다.
    - `item`의 `title`, `description`, `category`를 알맞는 html 태그에 넣으세요.
    - `item`은 `CardList.jsx`에서 전달됩니다.

- **기본 요구 사항**
    1. `npm install & npm run dev` 를 터미널에 입력하여 서버를 실행합니다. 
    2. `components/CardList.jsx` 를 수정한 뒤 `components/Card.jsx` 를  수정합니다.
    3. 문제의 **요구 사항**에 대해 구현합니다.
    4. css는 자유롭게 수정해도 좋습니다.
>>>>>>> fce307cbcbc405535e6fd6541db2fa0d9a94e858
