---
name: vibelearn
description: >-
  VibeLearn AI 학습 방법론 지원. 새 Topic 시작 시 templates/ 폴더 참조 필수.
  /vibelearn start → /vibelearn roadmap → /vibelearn daily 순서로 진행.
allowed-tools:
  - Read
  - Write
  - Bash
  - Glob
  - Grep
---
# VibeLearn AI Skill — 스킬 진입점

VibeLearn AI 학습 요청이 오면 아래 파일을 Read로 즉시 로드하세요:

`extras/vibelearnai-skill/SKILL.md`

절대 경로: `C:\AI_study\2026\VibeLearn-AI\extras\vibelearnai-skill\SKILL.md`

로드 후 워크플로우 타입 확인:
- **새 Topic**: /vibelearn start → topic_info.md → /vibelearn roadmap → /vibelearn daily 순서
- **Roadmap**: templates/roadmap_prompt_template.md 기반으로 vl_prompts/roadmap_prompt.md 생성
- **일일 학습**: daily_learning_prompt.md 로드 → Roadmap + WorkLog 분석 → 계획 제시
