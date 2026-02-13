# 아키텍처 구조

L0: Core (변경 불가 핵심 계약)
L1: Module (격리된 작업 단위)
L2: Orchestration (세션 통제)
L3: Integration Trigger (검증 후 통합)

Core → 분할 → 병렬세션 → 검증 → 통합 트리거
