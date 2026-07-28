# BBK Security Portfolio

배병권의 공개용 보안 포트폴리오 사이트입니다.

## 공개 기준

- 취약점관리 실적과 검증 가능한 연구·프로젝트만 공개합니다.
- 개인정보, 군 내부정보, 취약점 신고 원문, 비공개 저장소 링크는 포함하지 않습니다.
- 프로젝트 상태는 `PoC`, `개발 중`처럼 실제 검증 수준을 표시합니다.
- Computers & Security 연구는 `Accepted for publication` 상태로 표시하며 DOI·온라인 게재는 확정 후 반영합니다.

## 핵심 내용

- 취약점 1,138건 식별
- 1,054건 조치 지원
- 조치율 92.6%
- KVE 3건
- Computers & Security 단독저자 연구논문 게재 승인
- OPSHUB PoC
- MCP-Guard 개발 중

## 로컬 확인

정적 사이트이므로 저장소 루트에서 간단한 HTTP 서버로 확인할 수 있습니다.

```bash
python -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 엽니다.

## 배포

GitHub Pages의 `main` 브랜치 루트 배포를 기준으로 합니다.
