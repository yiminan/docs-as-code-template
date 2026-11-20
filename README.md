# Docs-as-code 프로젝트 템플릿

새 프로젝트에서는 `AGENTS.md`, `CLAUDE.md`, `docs/`, `.github/`를 저장소 루트에 배치합니다. 기존 프로젝트에 적용할 때는 기존 작업 지침, 문서 목차, PR 양식에 필요한 내용을 합칩니다.

## 첫 작업 계획

[문서 목차의 첫 작업 체크리스트](docs/README.md#첫-작업-계획)로 프로젝트 개요와 첫 기능 명세를 준비합니다.

PR을 작성할 때 [PR 양식](.github/pull_request_template.md)의 문서 확인 항목을 채웁니다. 리뷰에서는 연결한 문서가 변경 내용과 일치하는지 확인합니다. GitHub Actions는 저장소 루트와 `docs/`의 Markdown 파일에서 내부 링크와 앵커를 검사합니다.
