# Retired Projects

더 이상 손대지 않는 프로젝트들을 모아두는 곳입니다. 지우진 않았습니다 — 나중에 다시 볼 수도 있으니까요.

## 여기로 오는 기준

```mermaid
flowchart LR
    a[개인 프로젝트 시작] --> b{한동안 안 건드림}
    b -- 다시 씀 --> c[활성 조직으로 이동]
    b -- 안 씀 --> d[Retired-Projects로 이전]
```

### 보관 흐름

```mermaid
sequenceDiagram
    participant O as 소유자
    participant P as 프로젝트
    participant R as Retired-Projects
    O->>P: 한동안 방치
    O->>R: 정리 겸 이전
    R->>O: 필요하면 언제든 다시 꺼내볼 수 있음
```

## 대표 사례

- AIHQ / Quorum 계열 — 리브랜딩되어 지금의 Solomon으로 이어짐, 이전 이름의 버전들
- 각종 -legacy, -backup — 스냅샷용으로 남긴 것들
- 잠깐 만들다 만 사이드 프로젝트들
