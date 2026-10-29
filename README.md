# ikjun-study-log

CS 기술면접 대비 등 학습 아카이브

## 구조

```
Foundation/<category>/<NN>-<slug>/
├── material.md   ← 검색, 아티클, Claude 등으로 수집한 재료
└── note.md       ← 직접 쓴 정리
interviews/       ← 모의면접 기록
PROGRESS.md       ← 진행 현황 표
```

## 진행 현황

카테고리별 진행 표는 [PROGRESS.md](./PROGRESS.md)에서 관리한다.

## 커밋 컨벤션

```
docs(<category>): <주제> 재료      ← material.md 추가
docs(<category>): <주제> 정리      ← note.md 추가
fix(<category>): <주제> 검증 반영
docs(<category>): <주제> 재작성     ← 2주 후 다시 쓴 note.md
chore: ...                         ← 구조, 설정, README
```

`<category>`는 폴더명 사용 (예: `docs(javascript): 호이스팅/TDZ 재료`).
