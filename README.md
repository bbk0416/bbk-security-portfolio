# BBK Security Portfolio

취약점관리와 보안엔지니어링 경험을 정리한 공개 포트폴리오입니다.

군에서 취약점을 식별한 뒤 담당부서와 조치하고, 실제로 끝났는지 다시 확인하는 일을 해왔습니다. 공개 페이지에는 이 경험과 직접 연결되는 자료만 남기고, 확인되지 않은 성과나 과한 표현은 넣지 않습니다.

## 주요 실적

- 취약점 1,138건 식별
- 1,054건 조치 완료 확인
- 조치율 92.6%
- KVE 3건
- Computers & Security 171 (2026), Article 105085 단독저자

## 대표 프로젝트

- **VulnFlow** — 실무에서 해온 취약점 조치·재검증 흐름을 옮겨 만든 Free Public Beta
- **KillWeb** — Computers & Security에 게재한 단독저자 연구와 재현 자료
- **BreachScope** — Windows Event Log를 사건 흐름과 케이스로 연결하는 DFIR 도구
- **VulnSignal** — KEV·EPSS·CPE를 이용한 취약점 인텔리전스 포트폴리오 MVP

MCP-Guard, AuditSeal-CT, ORACLE-ZERO 같은 프로젝트는 지원 직무와 직접 관련이 있을 때만 보조자료로 사용합니다.

## 공개할 때 지키는 기준

개인정보, 군 내부정보, 취약점 신고 원문은 공개하지 않습니다. 합성 데이터나 로컬 테스트 결과도 실제 고객 환경이나 운영 환경에서 검증된 것처럼 쓰지 않습니다.

## 로컬 확인

```bash
python -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 열면 됩니다.

## 배포

GitHub Pages의 `main` 브랜치 루트에서 배포합니다.