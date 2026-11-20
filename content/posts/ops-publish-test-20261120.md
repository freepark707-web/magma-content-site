---
title: "운영 자동 발행 테스트 — 발행 API 7단계"
description: "6.1 7단계 운영 자동 발행 실습 검증용 글입니다. Vercel Production에서 GitHub 커밋으로 발행됩니다."
date: 2026-11-20
tags: ["테스트", "운영발행"]
---

## 운영 발행 검증

Vercel Production의 `POST /api/posts`가 GitHub Contents API로 커밋하는 경로를 확인하는 글입니다.

- 환경: Production (magma-content-site-phi.vercel.app)
- 저장: content/posts/ops-publish-test-20261120.md
- 기대 응답: 201 / mode github
