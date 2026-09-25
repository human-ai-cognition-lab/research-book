# research-book

Human-AI Cognition Lab의 연구 콘텐츠 소스입니다. [mdBook](https://rust-lang.github.io/mdBook/) 구조(`src/SUMMARY.md` + 챕터별 `.md` 파일)로 관리합니다.

## 로컬 미리보기 (선택)

mdBook이 설치되어 있다면:

```
mdbook serve
```

## 콘텐츠 추가 방법

1. `src/` 아래에 `.md` 파일 추가
2. `src/SUMMARY.md`에 `- [제목](경로.md)` 형식으로 등록
3. `main` 브랜치에 push하면 [human-ai-cognition-lab.github.io](https://github.com/human-ai-cognition-lab/human-ai-cognition-lab.github.io) 사이트가 자동으로 재빌드/배포됩니다.
