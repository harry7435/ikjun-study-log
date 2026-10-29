# 진행 현황

## 진행 범례

- 📦 재료 수집 (`material.md`)
- ✍️ 직접 정리 (`note.md`)
- 🔁 2주 후 재작성

완료된 칸에 해당 이모지를 표시한다.

## 1. JavaScript (`javascript`)

| #   | 주제                                                              | 📦  | ✍️  | 🔁  |
| --- | ----------------------------------------------------------------- | --- | --- | --- |
| 01  | var/let/const, 호이스팅, TDZ(Temporal Dead Zone)                  |     |     |     |
| 02  | 스코프(함수/블록/렉시컬), 클로저                                  |     |     |     |
| 03  | this 바인딩 4가지, 화살표 함수의 this                             |     |     |     |
| 04  | 프로토타입 체인, 클래스 문법과의 관계                             |     |     |     |
| 05  | 원시값 vs 참조값, 얕은/깊은 복사                                  |     |     |     |
| 06  | 비동기: 콜백 → Promise → async/await, Promise.all/race/allSettled |     |     |     |
| 07  | 모듈 시스템(CommonJS vs ES Modules), Tree Shaking                 |     |     |     |
| 08  | 이벤트 위임(Event Delegation), 버블링/캡처링                      |     |     |     |

## 2. 브라우저 동작 (`browser`)

| #   | 주제                                                                             | 📦  | ✍️  | 🔁  |
| --- | -------------------------------------------------------------------------------- | --- | --- | --- |
| 01  | 렌더링 파이프라인: 파싱 → DOM → CSSOM → Render Tree → Layout → Paint → Composite |     |     |     |
| 02  | Reflow(Layout) vs Repaint vs Composite 트리거 조건                               |     |     |     |
| 03  | Critical Rendering Path, 리소스 우선순위(preload/prefetch/dns-prefetch)          |     |     |     |
| 04  | async vs defer, script 태그 위치가 렌더링에 미치는 영향                          |     |     |     |
| 05  | 이벤트 루프, Call Stack, Web API, Task Queue, Microtask Queue                    |     |     |     |
| 06  | requestAnimationFrame, requestIdleCallback                                       |     |     |     |
| 07  | 브라우저 저장소 비교(Cookie/LocalStorage/SessionStorage/IndexedDB)               |     |     |     |
| 08  | 멀티 프로세스 아키텍처(Chrome의 렌더러/네트워크/GPU 프로세스)                    |     |     |     |

## 3. 네트워크 (`network`)

| #   | 주제                                                             | 📦  | ✍️  | 🔁  |
| --- | ---------------------------------------------------------------- | --- | --- | --- |
| 01  | HTTP/HTTPS, TLS handshake                                        |     |     |     |
| 02  | HTTP/1.1 vs HTTP/2 vs HTTP/3(QUIC, UDP 기반)                     |     |     |     |
| 03  | TCP 3-way handshake / UDP 차이                                   |     |     |     |
| 04  | CORS, Preflight(OPTIONS), Same-Origin Policy                     |     |     |     |
| 05  | RESTful API, HTTP 메서드와 멱등성                                |     |     |     |
| 06  | 캐시 헤더(Cache-Control, ETag, Expires, If-Modified-Since)       |     |     |     |
| 07  | 쿠키 vs LocalStorage vs SessionStorage, SameSite/HttpOnly/Secure |     |     |     |
| 08  | 인증 방식: JWT, OAuth, Session-Cookie                            |     |     |     |

## 4. React 렌더링/메모리/GC (`react`)

| #   | 주제                                                                                | 📦  | ✍️  | 🔁  |
| --- | ----------------------------------------------------------------------------------- | --- | --- | --- |
| 01  | Virtual DOM의 동작과 Reconciliation                                                 |     |     |     |
| 02  | React 렌더링 트리거(state/props 변경, 부모 리렌더)                                  |     |     |     |
| 03  | React.memo, useMemo, useCallback의 차이와 함정(레퍼런스 동일성)                     |     |     |     |
| 04  | key prop과 index를 key로 쓰면 안 되는 이유                                          |     |     |     |
| 05  | SSR vs CSR vs SSG vs ISR, Hydration                                                 |     |     |     |
| 06  | V8 메모리 구조: Stack / Heap / New Space(Scavenger) / Old Space                     |     |     |     |
| 07  | Mark-and-Sweep 가비지 컬렉션, 도달 가능성(reachability)                             |     |     |     |
| 08  | 메모리 누수 패턴: 미해제 이벤트 리스너, 클로저로 인한 참조, 전역 변수, detached DOM |     |     |     |

## 5. 자료구조 & 알고리즘 (`data-structures`)

| #   | 주제                                             | 📦  | ✍️  | 🔁  |
| --- | ------------------------------------------------ | --- | --- | --- |
| 01  | 배열 vs 링크드 리스트                            |     |     |     |
| 02  | 해시 테이블(JS Object/Map): 평균 O(1), 충돌 처리 |     |     |     |
| 03  | 스택, 큐, 덱                                     |     |     |     |
| 04  | 트리, 이진 탐색 트리, DOM 트리·가상 DOM 트리     |     |     |     |
| 05  | 그래프와 BFS/DFS                                 |     |     |     |
| 06  | 시간복잡도/공간복잡도, Big-O                     |     |     |     |

## 6. 운영체제 (`os`)

| #   | 주제                                | 📦  | ✍️  | 🔁  |
| --- | ----------------------------------- | --- | --- | --- |
| 01  | 프로세스 vs 스레드, 컨텍스트 스위칭 |     |     |     |
| 02  | 동기 vs 비동기, 블로킹 vs 논블로킹  |     |     |     |
| 03  | 멀티스레드와 JS 싱글 스레드의 차이  |     |     |     |
| 04  | 메모리 영역(코드/데이터/힙/스택)    |     |     |     |
| 05  | 웹 워커(Web Worker), 서비스 워커    |     |     |     |

## 7. 웹 보안 (`security`)

| #   | 주제                                                                   | 📦  | ✍️  | 🔁  |
| --- | ---------------------------------------------------------------------- | --- | --- | --- |
| 01  | XSS (Stored/Reflected/DOM-based)와 방어(이스케이프, CSP, DOMPurify)    |     |     |     |
| 02  | CSRF와 방어(CSRF Token, SameSite Cookie, Referer 검증)                 |     |     |     |
| 03  | CORS와 Same-Origin Policy                                              |     |     |     |
| 04  | HTTPS, TLS, 인증서 검증                                                |     |     |     |
| 05  | 인증·인가, JWT 저장 위치 트레이드오프(LocalStorage vs HttpOnly Cookie) |     |     |     |
| 06  | Clickjacking, X-Frame-Options, CSP                                     |     |     |     |

## 8. 기타 (`etc`)

| #   | 주제                        | 📦  | ✍️  | 🔁  |
| --- | --------------------------- | --- | --- | --- |
| 01  | Git                         |     |     |     |
| 02  | 빌드 도구                   |     |     |     |
| 03  | 테스트                      |     |     |     |
| 04  | 디자인 패턴                 |     |     |     |
| 05  | 성능 최적화/Core Web Vitals |     |     |     |
