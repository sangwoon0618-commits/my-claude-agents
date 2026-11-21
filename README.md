# My Claude Agents

Claude Code에서 쓰는 전문가 에이전트 283개 모음입니다.
원본: [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) (MIT 라이선스, 커밋 `8ae6164`). 라이선스 원문은 `LICENSE-agency-agents`에 있습니다.

## 사용법

### 클라우드 세션 (claude.ai/code)
이 저장소를 선택해서 세션을 시작하면 `.claude/agents/`의 에이전트가 자동으로 불러와집니다.

### 내 컴퓨터에 설치 (모든 프로젝트에서 사용)

macOS / Linux:

```bash
git clone https://github.com/sangwoon0618-commits/my-claude-agents.git && mkdir -p ~/.claude/agents && cp my-claude-agents/.claude/agents/*.md ~/.claude/agents/
```

Windows (PowerShell):

```powershell
git clone https://github.com/sangwoon0618-commits/my-claude-agents.git; New-Item -ItemType Directory -Force "$HOME\.claude\agents"; Copy-Item my-claude-agents\.claude\agents\*.md "$HOME\.claude\agents\"
```

설치 후 Claude Code를 다시 시작하세요.

### 호출 예시
- "Code Reviewer한테 이 코드 검토시켜줘"
- "Frontend Developer로 이 화면 만들어줘"
- "Meeting Notes Specialist로 회의록 정리해줘"
- "Korean Business Navigator한테 물어봐"

## 업데이트
원본 저장소의 최신 에이전트로 바꾸려면 Claude에게 "agency-agents 최신 버전으로 업데이트해줘"라고 요청하세요.
