# Kiro Team Template

팀 레포에 복사해서 쓰는 Kiro 설정 템플릿입니다.

## 사용법
1. 이 폴더의 내용(`.kiro/`, `.kiroignore`, `docs/`, `.github/`)을 팀 레포 루트에 복사합니다
2. `.kiro/steering/*.md`의 `TODO` 부분을 팀에 맞게 채웁니다
3. 커밋하고 push합니다
4. 팀원은 clone → Kiro IDE로 열기 → **워크스페이스 신뢰** → 설정에서 **Agent Ignore Files**에 `.kiroignore` 추가

## 들어 있는 것
| 경로 | 내용 |
|---|---|
| `.kiro/steering/` | 팀 규칙 (product / tech / structure / api-conventions / git-workflow) |
| `.kiro/skills/` | `/new-api`, `/pr-description`, `/sync-spec` |
| `.kiro/agents/` | `frontend`, `backend`, `reviewer` 커스텀 에이전트 |
| `.kiro/hooks/` | 에이전트 저장 시 lint, 응답 종료 시 비밀 값 검사 |
| `.kiro/settings/mcp.json` | GitHub MCP (토큰은 환경 변수) |
| `.kiro/specs/` | 기능별 Spec 폴더 (Kiro가 생성). 소유자 표는 `docs/specs.md` |
| `.kiro/workflows/` | 팀 공용 Workflow 레시피 저장 위치. 안내는 `docs/workflows.md` |
| `docs/api-contract.md` | 팀 공유 API 계약 (단일 출처) |
| `.kiroignore` | 에이전트가 읽으면 안 되는 파일 |
