# imhear-frontend

ImHear의 Vue 3 · TypeScript · Vite 저장소입니다. 담당 범위는 A의 금융 대시보드·차트, B의 모의투자·알림·STT/TTS·접근성 UI입니다.

## 계약과 검증

금융·모의주문 REST와 SSE는 Spring Boot를 통해 사용한다. 표시와 낭독에는 종목, 단위, 기준 시각을 포함한다.

인수 검증 기준은 시세 스냅샷과 SSE 재연결, 키보드만으로 주문 조건 확인 및 승인, 화면 낭독과 TTS 중복 여부입니다.

현재 폴더에는 협업 설정이 들어 있습니다. 서비스 코드와 테스트 하네스가 추가되면 이 위치에 설치, 실행, 검사 명령을 기록합니다. 네 저장소를 함께 여는 경우 상위 작업공간의 `docs/architecture/README.md`와 `docs/team-workflow.md`에서 공용 설계와 PR 흐름을 확인할 수 있습니다.

[에이전트 개발 지침](AGENTS.md)
