# 4장. HTML 과 JavaScript 연동하기

HTML 을 사용하면 브라우저에서 우리가 보여주고 싶은 UI (유저 인터페이스) 를 보여줄 수 있습니다. 만약에 사용자의 인터랙션 (상호작용) 에 따라 동적으로 UI 를 업데이트하고 싶다면, JavaScript 를 연동해주어야 합니다.

보통 인터랙션이 많은 경우에는 Vanilla JavaScript (별도의 라이브러리/프레임워크를 사용하지 않는 형태) 를 사용해서 하기에는 코드의 양도 많아지고 코드 관리도 어려운 편이라 보통 React, Vue, Angular 등의 도구를 사용합니다.

그래도, 해당 도구 없이 하는 기본적인 방법 또한 이해를 해둬야 앞으로 라이브러리/프레임워크를 공부하게 될 때 이해에 도움을 주므로, 간단한 예제 몇가지를 함께 만들어보겠습니다.