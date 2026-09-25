# korean-technical-writing

한국어 기술 문서를 작성·교정·검토하기 위한 에이전트 스킬입니다.

목표는 문장을 그럴듯하게 만드는 것이 아니라 다음 네 가지를 동시에 만족시키는 것입니다.

1. 기술적 사실과 검증 수준을 보존한다.
2. 모호한 표현을 한 가지로만 읽히게 만든다.
3. 내부 은어와 번역투를 평이하고 정확한 한국어로 바꾼다.
4. 이미 좋은 문장은 불필요하게 다시 쓰지 않는다.

## 포함 파일

- `SKILL.md` — 메인 작업 규칙과 라우팅
- `references/preservation-contract.md` — 숫자, 조건, 인과, 검증 수준 보존 규칙
- `references/korean-style.md` — 한국어 기술 문장 규칙
- `references/ambiguity-and-precision.md` — 모호성 제거 규칙
- `references/document-shapes.md` — 문서 유형별 기본 구조
- `references/review-checklist.md` — 최종 점검표
- `references/examples.md` — 예시
- `evals/cases.md` — 에이전트 동작을 확인할 평가 케이스

## 사용

폴더 전체를 사용하는 에이전트의 skills 디렉터리에 넣고 `korean-technical-writing` 스킬로 불러오면 됩니다.

특정 에이전트가 별도 frontmatter 필드나 디렉터리 규칙을 요구한다면 `SKILL.md`의 본문은 그대로 두고 메타데이터만 그 에이전트 형식에 맞추는 것을 권장합니다.

## License

MIT
