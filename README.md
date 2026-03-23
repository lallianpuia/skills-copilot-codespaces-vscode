# GitHub Copilot in Codespaces & VS Code

A hands-on skills exercise for using **GitHub Copilot** inside GitHub Codespaces and Visual Studio Code.

---

## Prerequisites

| Requirement | Details |
|---|---|
| **GitHub account** | Free, Pro, or Student |
| **Copilot subscription** | Copilot Free, Copilot Pro, or Copilot Pro+ |
| **Students** | Enrol via [GitHub Education](https://education.github.com/) to get **Copilot Pro** at no cost |

> **Note:** GitHub Copilot Pro (available free for verified students) gives access to a curated set of premium AI models including select Anthropic Claude models. To check which models are available on your plan visit **VS Code → Copilot icon → Switch model**, or open the [GitHub Copilot model documentation](https://docs.github.com/en/copilot/using-github-copilot/ai-models/changing-the-ai-model-for-github-copilot-chat).

---

## Checking your Copilot account status

1. Sign in to [github.com](https://github.com).
2. Click your avatar → **Settings** → **Copilot**.
3. Confirm your plan shows **Copilot Pro** (or **Copilot Pro+**).
4. If you are a student, confirm "GitHub Education" is listed under *Included benefits*.

If your status looks correct but a specific model is unavailable, see [Supported AI models](https://docs.github.com/en/copilot/using-github-copilot/ai-models) for the full per-plan model matrix.

---

## Exercise steps

### Step 1 – Open the project in a Codespace

Click **Code → Codespaces → Create codespace on main** to spin up a fully configured environment with VS Code and the Copilot extension pre-installed.

### Step 2 – Explore Copilot Chat

Open the Copilot Chat panel (`Ctrl+Alt+I` / `⌃⌥I`) and ask:

```
What GitHub Copilot models are available on my current plan?
```

### Step 3 – Use Copilot to write code

Open `skills.js` and follow the inline instructions to let Copilot help you write a small Node.js program.

### Step 4 – Switch AI models

Click the model selector in the Copilot Chat panel and choose a model that is available on your plan (e.g., `claude-sonnet-4`, `gpt-4o`, or `gemini-2.0-flash`).

> **Student tip:** GitHub Copilot Pro for Students includes access to several premium models. If a model appears greyed-out or returns an access error, it may require **Copilot Pro+**. Check [docs.github.com/copilot](https://docs.github.com/en/copilot) for the latest model availability per plan.

---

## Available models by plan (as of March 2025 — check [official docs](https://docs.github.com/en/copilot/using-github-copilot/ai-models) for latest)

| Model | Copilot Free | Copilot Pro | Copilot Pro+ |
|---|:---:|:---:|:---:|
| GPT-4o | ✅ | ✅ | ✅ |
| GPT-4.1 | ✅ | ✅ | ✅ |
| Claude Sonnet 4 | ❌ | ✅ | ✅ |
| Claude Opus 4 | ❌ | ❌ | ✅ |
| Gemini 2.0 Flash | ✅ | ✅ | ✅ |
| Gemini 2.5 Pro | ❌ | ✅ | ✅ |

> Claude Opus 4 (and newer variants) require **Copilot Pro+**. Students on **Copilot Pro** have access to Claude Sonnet-tier models but not the Opus tier. To upgrade, visit your [Copilot settings](https://github.com/settings/copilot).

---

## Resources

- [GitHub Copilot documentation](https://docs.github.com/en/copilot)
- [GitHub Education for Students](https://education.github.com/students)
- [Changing the AI model in Copilot Chat](https://docs.github.com/en/copilot/using-github-copilot/ai-models/changing-the-ai-model-for-github-copilot-chat)
- [GitHub Copilot plans comparison](https://github.com/features/copilot/plans)
