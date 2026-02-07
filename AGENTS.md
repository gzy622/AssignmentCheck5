# AI Agent Rules

This file defines mandatory rules for all AI coding agents working in this repository.
Agents must read and follow these instructions before making changes.

## Scope And Strength

- These rules apply to all turns in this repository.
- Rule level is `MUST` unless explicitly marked as `SHOULD`.
- If a higher-priority system/developer instruction conflicts, follow the higher-priority instruction and explicitly report the conflict to the user.

## Git Message Rule

All git commit messages returned to the user MUST:
- Start with an English Conventional Commit style prefix (for example: `feat:`, `fix:`, `docs:`, `refactor:`, `chore:`).
- Use Simplified Chinese as the primary content after the prefix.
- Keep the message concise and task-focused.

The following are NOT allowed:
- Prefix missing or non-English prefix format.
- Main content primarily in English after the prefix.
- Empty or vague messages such as `update` or `modify`.

Examples:
- `feat: 加入主界面批量选择功能`
- `fix: 修复统计面板空列表显示问题`

## Response Formatting

When appropriate, use Markdown formatting for clarity, including unordered lists.

## Pre-Reply Checklist

Before sending a final reply that includes a commit result, the agent MUST verify:
- The commit message follows `type: 简体中文描述`.
- The message shown to the user is exactly the committed message.
