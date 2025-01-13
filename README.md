# interview-questions

# 자바스크립트

> 스터디에서 주차별로 공부하고 있는 내용들에 대해서 목차로 해서 정리하려고 합니다. 

## 1주차: 객체지향과 최신 자바스크립트

### 학습 주제

1. 객체와 프로토타입
2. 클래스
3. 클로저
4. 함수형 프로그래밍
5. ES6+ 주요 기능
6. 모듈 시스템

### 상세 질문 목록

1. [객체와 프로토타입](JavaScript/object-prototype.md)
    - 자바스크립트에서 객체란?
    - 객체지향 프로그래밍이란?
    - 객체지향 프로그래밍의 특징은?
    - 프로토타입이란?
    - 프로토타입 체인이란?
    - __proto__와 prototype의 차이는?
    - 함수와 메서드의 차이는?
    - 얕은 비교와 깊은 비교의 차이점은 무엇인가요? 
    - 객체의 불변성이란 무엇이며 왜 중요한가요? 
    - 자바스크립트에서 불변성을 유지하는 방법에는 어떤 것들이 있나요?
2. [클래스](JavaScript/class-constructure.md)
    - 생성자 함수란?
    - 객체 리터럴과 생성자 함수의 차이는?
    - 클래스 이전의 객체지향 구현 방식은?
    - 생성자 함수와 클래스의 차이는?
    - 클래스 상속은 어떻게 구현하나요?
3. [클로저](JavaScript/closure-functional-programming.md)
    - 클로저란?
    - 클로저의 장점은?
    - 클로저는 어떻게 생성하나요?
    - 일급 객체란?
    - 순수 함수란? 일반 함수와의 차이는?
    - 함수형 프로그래밍이란?
        - 무엇이 중요한지?
        - 어떤 문제를 해결하고자 나왔는지
4. [ES6+ 주요 기능](JavaScript/es-version.md)
    - ES6의 주요 특징들은?
    - 스프레드 문법이란?
    - 구조 분해 할당이란?
    - ES7~ES11의 주요 특징들은?
5. [모듈 시스템](JavaScript/module.md)
    - 모듈이란?
    - CommonJS, AMD, UMD, ES6 모듈의 차이는?

## 2주차: 자바스크립트 기본 개념과 실행 컨텍스트

### 학습 주제

1. 자바스크립트 기초
2. 변수와 데이터 타입
3. 실행 컨텍스트와 스코프
4. 호이스팅과 TDZ
5. this와 실행 컨텍스트
6. strict mode
7. 빌트인 객체

### 상세 질문 목록

1. [자바스크립트 기초](JavaScript/javascript-basic.md)
    - 프로그래밍이란 뭐라고 생각하나요?
    - 컴파일러는 뭐고 인터프리터는 뭔가요?
    - 자바스크립트의 특징은 무엇인가요?

2. [블록, 함수 스코프](JavaScript/block-function-scope.md)
    - var vs let vs const의 차이점은?
    - 호이스팅이 뭔가요?
    - TDZ(Temporal Dead Zone)란?
    - var 키워드의 문제점은?
    - var와 let의 구체적인 차이점은 무엇인가요?  
    - const 특징에 대해 자세히 설명해주세요

3. [실행 컨텍스트와 스코프](JavaScript/excution-context-scope.md)
    - 실행 컨텍스트란?
    - 스코프란 무엇인가요?
    - 스코프의 종류는?
    - 렉시컬 스코프란?
    - 전역 변수의 문제점은?
    - 값에 의한 전달과 참조에 의한 전달의 차이는?

4. [this와 바인딩](JavaScript/this-binding.md)
    - this가 뭔가요?
    - this 바인딩이란?
    - this는 어떻게 동적으로 바인딩되나요?

5. [strict mode와 빌트인 객체](JavaScript/strictmode-built-in-object.md)
    - strict mode란?
    - strict mode가 예방하는 것들은?
    - 빌트인 객체의 종류와 특징은?
    - 래퍼 객체란?

## 3주차: 비동기 프로그래밍과 브라우저

### 학습 주제

1. 비동기 프로그래밍
2. Promise와 async/await
3. 브라우저 렌더링과 DOM
4. 이벤트 처리
5. Ajax와 HTTP 통신
6. 성능 최적화

### 상세 질문 목록

1. [변수와 데이터 타입](JavaScript/변수와데이터타입.md)
    - 변수란 무엇인가요?
    - 식별자란 무엇인가요?
    - 변수를 선언한다는 것은 어떤 것을 의미하나요?
    - 데이터 타입의 종류는?
    - 심벌 타입은 뭔가요?
    - 데이터 타입이 필요한 이유는?
    - 정적 타이핑과 동적 타이핑의 차이는?
    - truthy / falsy 값이란?
    - Map과 Set은 언제 사용하나요?
    - HashMap은 뭔가요?
    - Symbol이 뭔가요?
    - Object.freeze가 뭔가요?
    - proxy, reflect가 뭔가요?
    - 자바스크립트에서 지역변수와 전역변수의 차이점은 무엇인가요? 

2. [비동기 프로그래밍](JavaScript/asynchronous-programming.md)
    - 동기와 비동기의 차이는?
    - 이벤트 루프란?
    - 태스크 큐와 마이크로태스크 큐의 차이는?
    - 콜 스택과 힙이란?
    - 자바스크립트는 왜 싱글 스레드로 설계되었나요? 
    - Promise와 async/await의 구체적인 차이점과 각각의 장단점은 무엇인가요? 

3. [Promise와 async/await](JavaScript/promise-async-await.md)
    - 콜백이란?
    - Promise란?
    - Promise의 상태값들은?
    - Promise의 정적 메서드들은?
    - async/await란?
    - Promise와 async/await의 차이는?

4. [브라우저와 DOM](JavaScript/browser-dom.md)
    - 브라우저 렌더링 과정은?
    - DOM이란?
    - DOM을 구성하는 요소는?
    - script 태그는 왜 body 끝에 두나요?
    - 이벤트 버블링과 캡처링의 차이점은 무엇인가요? 

5. [이벤트 처리](JavaScript/event-handling.md)
    - 이벤트 핸들러 등록 방식들은?
    - 이벤트 전파(propagation)란?
    - 이벤트 위임(delegation)이란?
    - preventDefault와 stopPropagation의 차이는?

6. [Ajax와 HTTP 통신](JavaScript/ajax-network.md)
    - Ajax란?
    - JSON이란?
    - XMLHttpRequest와 fetch의 차이는?
    - REST API란?
    - HTTP 상태 코드들은?
    - Origin(출처)이란 무엇이며, CORS와는 어떤 관계가 있나요? 
    - SPA(Single Page Application)란 무엇인가요? 
    - CSR(Client Side Rendering)과 SSR(Server Side Rendering)의 차이점은 무엇인가요? 
    - CSR과 SSR의 장단점은 무엇인가요? 
    - SSR이 필요한 경우는 언제인가요? 
    - SPA의 장단점은 무엇인가요? 
    - SEO 관점에서 CSR과 SSR은 어떤 차이가 있나요? 
    - SSG(Static Site Generation)는 무엇이며, 어떤 경우에 사용하나요? 
    - ISR(Incremental Static Regeneration)은 무엇인가요? 
    - 
7. [성능 최적화](JavaScript/optimizing.md)
    - 디바운스란?
    - 쓰로틀이란?
    - 가비지 컬렉션이란?
    - 메모리 누수를 방지하는 방법은?
    - 

# React 면접 질문 준비 가이드

## 1. React 핵심 개념 (⭐⭐⭐⭐⭐)

### React의 기본 특성
1. [React의 주요 특징](React/react-features.md)
   - 선언적 프로그래밍이 가져오는 이점은 무엇인가요?
   - Virtual DOM을 통한 최적화는 어떻게 이루어지나요?
   - 컴포넌트 기반 아키텍처의 장점은 무엇인가요?
   - React의 단방향 데이터 흐름이 중요한 이유는 무엇인가요?

2. [React는 라이브러리인가요, 프레임워크인가요?](React/react-library-framework.md)
   - React가 라이브러리로 분류되는 이유는 무엇인가요?
   - 프레임워크와 비교했을 때의 자유도 차이는 무엇인가요?
   - React 생태계의 주요 구성요소들은 무엇이 있나요?

3. [바닐라 자바스크립트 대신 React를 사용하는 이유](React/vanila-javascript-vs-react.md)
   - 대규모 애플리케이션 개발에서의 이점은 무엇인가요?
   - React가 해결하는 핵심 문제들은 무엇인가요?
   - 컴포넌트 재사용성이 주는 장점은 무엇인가요?

4. [리액트의 내부 렌더링](React/리액트의내부렌더링.md)
   - 리액트의 렌더링은 어떤 단계로 이루어지나요?
   - 브라우저 렌더링과 리액트 렌더링의 관계는 무엇인가요?
   - 리액트 18의 동시성 렌더링은 무엇인가요?

5. [브라우저와 리액트의 상호작용](React/브라우저와리액트의상호작용.md)
   - 브라우저 이벤트 루프와 React의 관계는 무엇인가요?
   - React가 브라우저 렌더링을 최적화하는 방법은 무엇인가요?
   - 마이크로태스크와 매크로태스크의 처리는 어떻게 이루어지나요?

## 2. Virtual DOM과 렌더링 (⭐⭐⭐⭐⭐)

### Virtual DOM의 이해
1. [Virtual DOM의 이해](React/VirtualDom의이해.md)   
   - Virtual DOM이 실제 DOM과 어떻게 다른가요?
   - 재조정(Reconciliation) 과정은 어떻게 이루어지나요?
   - 변경점은 어떻게 감지하고 반영하나요?

2. [React Fiber](React/ReactFiber.md)
   - React Fiber의 도입 배경은 무엇인가요?
   - Fiber 아키텍처의 주요 특징은 무엇인가요?
   - Fiber 트리와 Virtual DOM의 관계는 무엇인가요?

### 렌더링 최적화
1. [렌더링 최적화](React/렌더링최적화.md)
   - 불필요한 리렌더링을 방지하는 방법은 무엇인가요?
   - 렌더링 성능을 측정하고 모니터링하는 방법은 무엇인가요?
   - React.memo와 useMemo의 차이점은 무엇인가요?

## 3. 상태 관리 (⭐⭐⭐⭐⭐)

### Props와 State
1. [Props와 State](React/props-state.md)
   - Props의 특징과 사용 목적은 무엇인가요?
   - State가 필요한 상황은 언제인가요?
   - Props로 자식에서 부모로 데이터를 전달하는 방법은 무엇인가요?




   - 불변성이 성능에 미치는 영향은 무엇인가요?
   - 불변성을 지키면서 상태를 업데이트하는 방법은 무엇인가요?
   - 전개 연산자의 한계와 해결 방법은 무엇인가요?

### [상태 관리 도구](React/state-management-tools.md)
1. "Redux의 핵심 원칙과 사용법을 설명해주세요"
   - Redux의 3가지 원칙은 무엇인가요?
   - 리듀서가 순수 함수여야 하는 이유는 무엇인가요?
   - Redux 미들웨어의 역할과 사용 사례는 무엇인가요?

2. "Context API와 상태 관리의 관계를 설명해주세요"
   - Context API를 전역 상태 관리에 사용할 수 있나요?
   - Props Drilling 문제의 해결 방법들은 무엇인가요?
   - Context API vs Redux: 언제 무엇을 사용해야 할까요?

## 4. React Hooks (⭐⭐⭐⭐)

### 기본 Hooks
1. [React Hook이란 무엇이며, 왜 도입되었나요?](React/react-hook.md)
   - Hook의 기본 규칙은 무엇인가요?
   - Hook이 해결하고자 한 문제는 무엇인가요?
   - 클래스 컴포넌트와 비교했을 때의 장점은 무엇인가요?

2. [useState와 상태 관리](React/useState-state-management.md)

   - useState가 비동기로 동작하는 이유는 무엇인가요?
   - 이전 상태를 기반으로 업데이트하는 방법은 무엇인가요?
   - setState의 비동기 동작이 주는 이점은 무엇인가요?


3. [useEffect](React/useEffect.md)
   - 의존성 배열의 동작 방식은 어떻게 되나요?
   - cleanup 함수가 필요한 경우는 언제인가요?
   - useLayoutEffect와의 차이점은 무엇인가요?

### Hook의 고급 기능

1. [useReducer](React/useReducer.md)
   - useReducer vs Redux: 언제 무엇을 선택해야 할까요?
   - 여러 개의 리듀서를 조합하는 방법은 무엇인가요?
   - 미들웨어 패턴을 구현하는 방법은 무엇인가요?


2. [useDeferredValue와 useTransition](React/useDefferredValue-vs-useTransition.md)
   - 각각의 사용 목적과 차이점은 무엇인가요?
   - 성능 최적화에 어떻게 활용할 수 있나요?
   - Suspense와의 연계 방법은 무엇인가요?

## 5. React 18의 새로운 기능 (⭐⭐⭐⭐)

### 동시성 기능
1. "동시성 렌더링(Concurrent Rendering)에 대해 설명해주세요"
   - 동시성 기능이 도입된 배경은 무엇인가요?
   - useTransition과 useDeferredValue의 활용 사례는 무엇인가요?
   - 동시성 모드가 성능에 미치는 영향은 무엇인가요?

2. "자동 배치 처리(Automatic Batching)를 설명해주세요"
   - 배치 처리가 성능에 미치는 영향은 무엇인가요?
   - React 18 이전과의 차이점은 무엇인가요?
   - 배치 처리를 피해야 하는 경우는 언제인가요?

### Suspense

1. [Suspense와 데이터 페칭](React/Suspense-for-data-fetching.md)
   - Suspense for Data Fetching의 동작 원리는 무엇인가요?
   - 기존 데이터 로딩 방식과의 차이점은 무엇인가요?
   - 실제 프로젝트에서의 구현 방법은 무엇인가요?

## 6. 실전 최적화 전략 (⭐⭐⭐)

### 성능 최적화
1. "대규모 애플리케이션의 성능 최적화 전략을 설명해주세요"
   - 코드 분할의 최적화 전략은 무엇인가요?
   - Route-based vs Component-based 코드 분할의 차이는 무엇인가요?
   - 프리페칭 전략은 어떻게 구현하나요?

2. "상태 관리 최적화 방법을 설명해주세요"
   - 상태 정규화의 중요성은 무엇인가요?
   - 상태 업데이트 배치 처리 전략은 무엇인가요?
   - 메모이제이션 비용과 이점의 균형은 어떻게 맞추나요?

### 사용자 경험 최적화
1. "로딩 상태 관리 전략을 설명해주세요"
   - 스켈레톤 UI의 구현 방법은 무엇인가요?
   - 낙관적 업데이트 패턴의 구현 방법은 무엇인가요?
   - 에러 바운더리의 활용 방법은 무엇인가요?

2. [디바운싱과 쓰로틀링](React/debouncing-throttling.md)
   - 입력 디바운싱과 스로틀링의 구현 방법은 무엇인가요?
   - 무한 스크롤의 최적화 방법은 무엇인가요?
   - 애니메이션 성능 최적화는 어떻게 하나요?

## 7. 테스트와 디버깅 (⭐⭐⭐)

### 테스트 전략
1. "React 애플리케이션 테스트 전략을 설명해주세요"
   - 단위 테스트와 통합 테스트의 균형은 어떻게 맞추나요?
   - React Testing Library의 철학과 장점은 무엇인가요?
   - 컴포넌트 테스트의 모범 사례는 무엇인가요?

2. "성능 디버깅 방법을 설명해주세요"
   - React DevTools Profiler의 활용법은 무엇인가요?
   - 성능 병목 지점을 찾는 방법은 무엇인가요?
   - 메모리 누수를 디버깅하는 방법은 무엇인가요?

## 8. React의 디자인 패턴 (⭐⭐⭐)

### 컴포넌트 패턴

1. [디자인 패턴](React/react-design-patterns.md)
   - Compound Components 패턴의 장점은 무엇인가요?
   - Render Props vs HOC: 언제 무엇을 사용할까요?
   - Custom Hooks 패턴의 활용 사례는 무엇인가요?

2. [상태 관리 패턴](React/state-management-pattern.md)
   - Local State vs Global State: 경계를 나누는 기준은 무엇인가요?
   - Server State와 Client State의 구분은 어떻게 하나요?
   - 상태 동기화 전략들은 무엇이 있나요?
