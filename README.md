# research-book

Human-AI Cognition Lab의 연구 기록 저장소입니다. 인간-AI 협업, 인지, 센스메이킹, LLM 인지 연구에 관한 글을 씁니다.

이 문서는 이 프로젝트에 처음 참여하시는 분을 위한 안내입니다.

## 1. 참여 신청 (처음이신가요?)

이 저장소에 글을 쓰려면 먼저 편집 권한을 받아야 합니다.

1. GitHub 계정이 없다면 https://github.com/signup 에서 가입
2. 아래 정보를 **e.jongok@gmail.com** 으로 보내 초대 요청
   - GitHub 아이디 (username)
   - (선택) 관심 있는 연구 주제나 역할
3. 초대가 오면(GitHub 알림 또는 이메일) 수락 — 이후 바로 아래 2번처럼 편집할 수 있습니다.

## 2. 브라우저에서 바로 글쓰기 (설치 없이)

컴퓨터에 아무것도 설치하지 않고 GitHub 웹사이트에서 바로 작성할 수 있습니다.

**새 글 추가하기**
1. 이 저장소의 [`src` 폴더](https://github.com/human-ai-cognition-lab/research-book/tree/main/src)로 이동
2. **Add file → Create new file** 클릭
3. 파일 이름 입력 (예: `sensemaking/my-note.md`)
4. 내용 작성 (마크다운)
5. 페이지 하단에서 **Commit directly to the main branch** 선택 후 **Commit new file**

**기존 글 수정하기**
1. 수정할 `.md` 파일 열기
2. 우측 상단 연필(✏️) 아이콘 클릭
3. 수정 후 하단에서 커밋

> 더 편한 에디터가 필요하면 주소창에서 `github.com`을 `github.dev`로 바꿔 접속하세요 (예: `github.dev/human-ai-cognition-lab/research-book`) — VS Code와 동일한 웹 에디터가 열립니다.

## 3. 새 글을 사이트 메뉴에 노출시키기

새 파일을 추가했다면 `src/SUMMARY.md`에도 한 줄 등록해야 사이트에 나타납니다.

```
- [내 글 제목](sensemaking/my-note.md)
```

`main` 브랜치에 커밋하면 별도 조치 없이 자동으로 https://human-ai-cognition-lab.github.io/ 에 반영됩니다 (보통 1~2분 이내).

## 4. 로컬에서 작업하고 싶다면 (선택)

```
git clone git@github.com:human-ai-cognition-lab/research-book.git
```

[mdBook](https://rust-lang.github.io/mdBook/guide/installation.html)이 설치되어 있다면 `mdbook serve`로 로컬 미리보기가 가능합니다.

## 구조

- `src/SUMMARY.md` — 목차 (사이트 사이드바 순서를 결정)
- `src/*.md` — 실제 글
