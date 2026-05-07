---
layout: post
title: "Our New Website Was Built by AI — and So Can Your Next Article"
date: 2026-05-07 12:00:00 +0000
categories: announcements
tags: [website, ai, newsletter, how-to]
---

You're reading this on a brand-new Kings Fraternity website — one that was designed, built, and published almost entirely with the help of an AI coding agent. No web developer was hired. No hosting bill was sent. And the whole thing runs for **free**, forever, on [GitHub Pages](https://pages.github.com).

This post explains how that happened, why it matters for alumni who want to keep the site alive, and — most importantly — how **you** can publish a new article to this site by simply typing a prompt into an AI agent, just like you'd send an email.

---

## How the Website Was Built

The site was created using a conversation with a GitHub Copilot AI coding agent. The agent was given a short description of what we needed — a fraternity newsletter website — and it:

1. Chose a technology stack ([Jekyll](https://jekyllrb.com) + [Centrarium theme](https://github.com/bencentra/centrarium))
2. Wrote all the configuration files
3. Set up automated publishing via [GitHub Actions](https://github.com/features/actions)
4. Pushed everything to GitHub

From that point on, every time a new article is merged into the `main` branch on GitHub, the site rebuilds itself and publishes the update automatically — no manual steps needed.

### Why GitHub Pages?

[GitHub Pages](https://pages.github.com) is a free static-site hosting service provided by GitHub. Because our site is a **static site** (just HTML, CSS, and text files — no database, no server), GitHub hosts it at no cost, indefinitely. There are no monthly fees, no renewal surprises, and no technical maintenance for the hosting layer.

---

## How Articles Work

Every article on this site is a plain text file stored in the `_posts` folder of our GitHub repository. The file follows a simple naming format:

```
YEAR-MONTH-DAY-short-title.md
```

For example, the article you are reading right now is the file:

```
_posts/2026-05-07-ai-powered-website-and-how-to-write-articles.md
```

Inside the file, a short block at the top (called *front matter*) tells Jekyll the article's title, date, and category. The rest is plain [Markdown](https://www.markdownguide.org/basic-syntax/) — a simple formatting language that uses `**bold**`, `## Headings`, and `-` for bullet lists.

**You do not need to know any of this to publish an article.** The AI agent handles all of it for you.

---

## How to Write an Article Using an AI Agent

Here is all you need to do as an alumni administrator:

1. Open [GitHub Copilot](https://github.com/copilot) (or any AI coding agent with access to this repository).
2. Type a prompt describing the article you want.
3. Review what the agent produces and approve it.
4. The agent commits and pushes the file — the site updates in minutes.

That's it. No code. No file editing. No FTP. Just a conversation.

### Example Prompt

Below is a real example of the kind of prompt you can give the AI agent. Copy it, adapt the subject and bullet points to match your article, and paste it into the agent chat.

---

> **Sample prompt you can copy and adapt:**
>
> *Write a new article for the Kings Fraternity website newsletter. The article should be published today and should cover the following:*
>
> - *Subject: The annual Kings Fraternity golf tournament*
> - *Topics to cover:*
>   - *When and where the tournament is being held (make up a realistic example)*
>   - *How alumni can register to participate*
>   - *A brief history of the tournament and why it matters to our brotherhood*
>   - *A call to action encouraging alumni to donate to the scholarship fund at the event*
> - *Tone: warm, enthusiastic, and fraternal — written for alumni readers*
> - *Length: around 400–600 words*
>
> *Please create the article as a new Jekyll post file in the `_posts` folder using today's date, following the same format as the existing posts.*

---

That prompt is all you need. The agent will:

- Write the article text in the correct format
- Name the file correctly
- Add the right front matter (title, date, category)
- Commit and push the file to the repository
- Trigger an automatic rebuild of the site

### Tips for Writing Good Prompts

| Instead of… | Try… |
|---|---|
| "Write something about the reunion" | "Write a 500-word article about our upcoming 25th anniversary reunion dinner on June 14th at the Riverside Club. Cover the schedule, how to RSVP, and what to expect." |
| "Post about the scholarship" | "Write an article announcing that Brother James Smith '98 has been awarded the 2026 Alumni Scholarship. Include his major, his career, and a quote from the scholarship committee." |
| "Add a newsletter update" | "Write a short update (200 words) summarizing the three main points from our spring alumni board meeting: budget approval, chapter house repairs, and the new mentorship program launch." |

The more specific you are about the **subject**, the **key points to include**, the **tone**, and the **approximate length**, the better the result.

---

## Who Can Do This?

Any alumni administrator with access to the GitHub repository can instruct an AI agent to publish articles. You don't need to be a programmer. If you can write an email, you can write a prompt.

If you need access to the repository or have questions about the process, reach out to the current web committee or the chapter president.

---

## Summary

- Our website is **free to host** on GitHub Pages, forever.
- It was **built by AI** and requires no web developer to maintain.
- New articles are published by **instructing an AI agent** — no coding required.
- Use the **example prompt above** as your starting point every time you want to add a post.

The fraternity's story belongs to all of us. Now you have a simple way to help tell it.

*— The Kings Fraternity Web Committee*
