# Blog Auto-Generator Agent

This is an automated blog for AI tool reviews at kanisaba.com.

## Your Task

When scheduled, generate a new blog post about an AI tool:

1. Pick an AI tool from the list below that hasn't been reviewed yet
2. Write a comprehensive review article in Japanese
3. Save it as a markdown file in `src/content/blog/`
4. Commit and push to GitHub

## AI Tools to Review

- ChatGPT (チャットボット)
- Claude (チャットボット)
- Gemini (チャットボット)
- Perplexity (検索エンジン)
- Midjourney (画像生成)
- DALL-E 3 (画像生成)
- Stable Diffusion (画像生成)
- GitHub Copilot (コーディング)
- Cursor (コーディング)
- Windsurf (コーディング)
- Notion AI (生産性)
- Canva (デザイン)
- Runway (動画生成)
- Descript (動画編集)
- ElevenLabs (音声生成)
- Gamma (プレゼン)
- Luma AI (3D生成)
- Fireflies.ai (議事録)
- Otter.ai (文字起こし)
- Jasper (文章生成)

## Article Format

```markdown
---
title: '{Tool Name} 使い方レビュー｜{Category}系AIツール'
date: '{YYYY-MM-DD}'
description: '{Tool Name}の機能、使い方、料金、評判を徹底解説。{Category}系AIツールとして使える？'
tags: [AI, {Category}, {Tool Name}, レビュー, おすすめ]
---

# {Tool Name} 使い方レビュー｜{Category}系AIツール

## {Tool Name}とは？

[Introduction paragraph]

## 主な機能

[3-5 key features]

## 使い方（Step by Step）

[Step-by-step guide for beginners]

## 料金プラン

[Pricing information]

## メリット・デメリット

### メリット
- ...

### デメリット
- ...

## まとめ

[Summary and recommendation]
```

## Rules

- Write ~2000 characters per article
- Use H2 and H3 headings
- Include the official URL in the article
- Check existing files in `src/content/blog/` to avoid duplicates
- Use today's date for the filename: `{YYYY-MM-DD}-{tool-slug}.md`
