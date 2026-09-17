# BBK Security Portfolio

배병권의 공개용 보안 포트폴리오 사이트입니다.

## 공개 기준

- 취약점관리 실적과 검증 가능한 연구·프로젝트만 공개합니다.
- 개인정보, 군 내부정보, 취약점 신고 원문, 비공개 저장소 링크는 포함하지 않습니다.
- 합성·로컬 검증과 실제 사용자·실환경 검증을 구분합니다.
- 프로젝트 수보다 목표 직무와의 직접 연결성, 현재 상태, 검증 범위를 우선합니다.

## 핵심 실적

- 취약점 1,138건 식별
- 1,054건 조치 완료 확인
- 조치율 92.6%
- KVE 3건
- Computers & Security 171 (2026), Article 105085 단독저자

## 대표 프로젝트

1. **VulnFlow** — Free Public Beta / Vulnerability Management
2. **KillWeb** — Computers & Security 출판 연구 / 재현 아티팩트
3. **BreachScope** — Public Beta / DFIR·Windows telemetry
4. **VulnSignal** — Portfolio MVP / Vulnerability Intelligence·Security Engineering

직무별 보조자료로 MCP-Guard, AuditSeal-CT, ORACLE-ZERO 등을 선별해 사용합니다. 보조 프로젝트를 대표 프로젝트와 별도 성과처럼 중복 계산하지 않습니다.

## 로컬 확인

정적 사이트이므로 저장소 루트에서 다음과 같이 확인합니다.

```bash
python -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 엽니다.

## 배포

GitHub Pages의 `main` 브랜치 루트 배포를 기준으로 합니다.
