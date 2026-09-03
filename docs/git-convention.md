# git convention

깃 컨벤션을 정의합니다.

### 커밋 타입 정의

- `feat`: 신규 기능 추가할 때 (e.g - 마이그레이션 스킬 추가)
- `fix`: 버그 수정할 때 (e.g - 스킬 버그 수정)
- `docs`: 단순 문서 추가할 때
- `style`: 디자인시스템 수정할 때
- `refactor`: 프롬프트 최적화할 때 (e.g CLAUDE 프롬프트 수정)
- `chore`: 하기 싫은 일 (e.g - 문서 오타 수정, 파일 정리)

### 커밋 포맷

```
type : (task) subject

- body
```

### 커밋 예시

- Task 번호: `TASK-1`
- 작업 내용: DESIGN.md 마이그레이션 클로드 스킬 추가
```
feat : (TASK-1) DESIGN.md 마이그레이션 클로드 스킬 추가

- xxxxx
```