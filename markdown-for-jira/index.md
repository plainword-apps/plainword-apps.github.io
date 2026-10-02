---
title: Markdown for Jira
---

# Markdown for Jira

Edit Jira issue descriptions in Markdown, with a live preview of exactly how Jira will show them.

## Using it

1. Open an issue and click **•••** (top right), then **Edit in Markdown**.
2. Edit the Markdown on the left; the preview on the right shows what Jira will display.
3. Click **Save**. Anything you didn't change is saved exactly as it was.

Paste answers from ChatGPT or Claude straight in: tables, lists, code blocks and checklists come through.

## The Markdown

Ordinary Markdown works as you'd expect: `#` headings, `**bold**`, `_italic_`, `~~struck~~`, `` `code` ``,
`[links](https://example.com)`, `-` and `1.` lists, `>` quotes, fenced code blocks and `| tables |`.

Jira's own pieces use forms you may know from GitHub:

| In Jira | In Markdown |
| --- | --- |
| Checklist | `- [ ] To do` and `- [x] Done` |
| Info / note / success / warning / error panel | `> [!NOTE]`, `> [!IMPORTANT]`, `> [!TIP]`, `> [!WARNING]`, `> [!CAUTION]` on the first line of a quote |
| Expand | `<details>`, then `<summary>Title</summary>`, a blank line, the content, and `</details>` |
| Underline, subscript, superscript, colour | `<u>…</u>`, `<sub>…</sub>`, `<sup>…</sup>`, `<span style="color: #ff5630">…</span>` |
| Mention | `[@Sam Lee](mention:…)` |
| Status label | `[IN REVIEW](status:blue)` |
| Date | `[2026-11-14](date:)` |
| Smart link | `<card:https://…>` |
| Attached image | `![screenshot.png](media:…)` |

Mentions, status labels, dates and images keep the details Jira needs in the link, so leave those as they are.
Anything Markdown can't express (merged table cells, for example) appears as a block marked `adf`: leave it
unchanged and it's saved exactly as it was.

## Good to know

- The app edits as you, so Jira's own permissions apply.
- If someone else saves the description while you're editing, nothing is overwritten and the editor tells you.
- The app stores nothing and sends nothing outside Atlassian. [Privacy policy](privacy.html) ·
  [Terms of use](terms.html)

## Support

Email [plainwordapps@outlook.com](mailto:plainwordapps@outlook.com).
