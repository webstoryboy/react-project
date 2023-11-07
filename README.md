# react를 이용한 포트폴리오 사이트 만들기
React.js는 사용자 인터페이스를 만들기 위한 JavaScript 라이브러리입니다. Facebook에서 개발했으며, 웹 애플리케이션의 UI를 구축하는 데 사용됩니다. React는 단일 페이지 애플리케이션 또는 복잡한 웹 애플리케이션에서 컴포넌트 기반의 접근 방식을 사용하여 UI를 만들 수 있도록 돕습니다.   
    
React는 가상 DOM(Virtual DOM)을 활용하여 성능을 향상시키고, UI를 업데이트할 때 실제 DOM 조작을 최소화하여 빠르고 효율적인 방식으로 작동합니다. 컴포넌트 기반 아키텍처를 사용하기 때문에 UI를 작은 조각으로 나누어 개발하고, 각 컴포넌트는 독립적으로 상태(state)를 가질 수 있습니다.     
    
또한, React는 JSX(JavaScript XML)라는 문법을 제공하여 JavaScript 코드 안에 HTML과 유사한 마크업을 작성할 수 있게 해주어, 코드의 가독성과 유지보수성을 높여줍니다. React는 확장성이 뛰어나며, 추가적으로 상태 관리를 위한 라이브러리인 Redux나 상태 관리 기능을 갖춘 React의 Context API와 같은 도구들과 결합하여 더욱 강력한 기능을 제공합니다.

## 작업 순서
1. 리액트 설치
2. git에 업로드
3. [lenis 사이트](https://github.com/studio-freight/lenis)

## 설치
1. react 설치 `npx create-react-app 프로젝트 이름`
2. gsap 설치 `npm i gsap`
3. sass 설치 `npm i sass`
4. lenis 설치 `npm i @studio-freight/lenis`

## 트러블 슈팅
<details>
<summary>Whitespace 에러 </summary>
유닉스 시스템에서는 한 줄의 끝이 LF(Line Feed)로 이루어지는 반면,
윈도우에서는 줄 하나가 CR(Carriage Return)와 LF(Line Feed), 즉 CRLF로 이루어지는데
Git이 이 둘 중 어느 쪽을 선택할지 혼란이 온 것이다!

해결방법   
`git config --global core.autocrlf true // 시스템 전체에 적용`   
`git config core.autocrlf true // 해당 프로젝트에만 적용`   
</details>
