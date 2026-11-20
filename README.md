# Docs-as-code 프로젝트 템플릿

새 저장소에 이 템플릿을 적용하거나, 기존 저장소의 지침과 문서 목차에 필요한 파일을 합칩니다.

## 첫 작업 계획

- [ ] [프로젝트 개요](docs/product/overview.md)에 사용자, 문제, 첫 출시 범위를 적습니다.
- [ ] [AGENTS.md](AGENTS.md)에 이 프로젝트의 실행·검증 명령을 추가합니다.
- [ ] [기능 명세 양식](docs/features/_template.md)으로 첫 기능의 인수 조건을 정리합니다.
- [ ] 첫 기능에 등장하는 용어를 [용어집](docs/domain/glossary.md)에 추가합니다.
- [ ] 모듈 경계와 데이터 흐름이 정해지면 [아키텍처 개요](docs/architecture/overview.md)를 갱신합니다. 설계 결정의 근거는 [ADR 양식](docs/adr/_template.md)에 기록합니다.

[문서 목차](docs/README.md)에 작성한 문서를 연결합니다. GitHub Actions는 PR에서 저장소 내부의 Markdown 링크와 문서 앵커를 검사합니다.
