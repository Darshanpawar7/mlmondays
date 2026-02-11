<div align="center">

# ML Mondays

**The Official Blog Space of NeuralHive — AI/ML Club, PES University EC Campus**

[![Astro](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://www.netlify.com)
[![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://www.markdownguide.org)

*Making complex concepts clear, meaningful, and inspiring — one Monday at a time.*

[View Site](https://github.com/neuralhive-ec/mlmondays) | [Report Issue](https://github.com/neuralhive-ec/mlmondays/issues) | [Contribute](#-contributing)

</div>

---

## About

**ML Mondays** is a curated space for learning, curiosity, and thoughtful writing around Machine Learning and Artificial Intelligence. Whether you're just beginning your ML journey or diving deep into advanced ideas, this platform is built for you.

This is an initiative by **NeuralHive**, the student-run AI/ML community at PES University EC Campus. We focus on building strong intuition, practical skills, and a culture of sharing through well-crafted technical writing.

### Our Principles

| | Principle | |
|:---:|:---|:---|
| **01** | Learning is strongest when shared | *Community over competition* |
| **02** | Intuition matters as much as implementation | *Depth over surface-level understanding* |
| **03** | Clarity beats complexity | *Communicate to teach, not to impress* |

---

## Tech Stack

| Technology | Purpose |
|:---|:---|
| **Astro** | Static site framework |
| **Tailwind CSS** | Utility-first styling |
| **Netlify** | Deployment & hosting |
| **Markdown** | Blog content authoring |
| **Dynamic Routing** | `[slug].astro` for blog posts |

---

## Features

- Clean minimal design with dark theme
- Dynamic blog routing with slug-based URLs
- Dedicated **Blog Vault** with real-time search
- Glassmorphic UI elements and interactive hover animations
- Theme-aware styling across all components
- Structured layouts — Home, About, Posts, Ethos

---

## Contributors

<table>
  <tr>
    <td align="center"><strong>Darshan Pawar</strong></td>
    <td align="center"><strong>Sanmitra</strong></td>
    <td align="center"><strong>Rakshan</strong></td>
  </tr>
  <tr>
    <td>
      Initial codebase & project structure<br>
      Core pages & layouts<br>
      Dark theme design<br>
      Astro + Tailwind config<br>
      Netlify deployment<br>
      Content & asset management
    </td>
    <td>
      <code>BaseLayout</code> & homepage UI enhancements<br>
      Navigation layout & styling<br>
      Dynamic routing updates<br>
      UI component refactoring<br>
      Favicon & minor fixes
    </td>
    <td>
      Glassmorphic layout & manifesto grid<br>
      Blog vault with real-time search<br>
      Interactive hover animations<br>
      Theme-aware styling refinements
    </td>
  </tr>
</table>

---

## Contributing

We welcome contributions from NeuralHive members and collaborators. This is a learning-first codebase — clean contributions, thoughtful commits, and readable code matter.

### Open Contribution Areas

<details>
<summary><strong>1. Keyword Slugs for Blogs</strong></summary>

- Add keyword-based slugs for each blog post
- Improve SEO and search discoverability
- Standardize slug generation logic

```
/posts/understanding-transformers-intuition-guide
```

</details>

<details>
<summary><strong>2. Automated Upload Pipeline</strong></summary>

- Accept blog submissions in Markdown
- Validate frontmatter automatically
- Push updates to the repository on approval
- Implementation options: GitHub Actions, CLI tool, or admin portal

</details>

<details>
<summary><strong>3. Frontmatter Standardization & Validation</strong></summary>

Enforce required fields before deployment:

| Field | Required |
|:---|:---:|
| `title` | Yes |
| `description` | Yes |
| `date` | Yes |
| `author` | Yes |
| `tags` | Yes |
| `slug` | Yes |

</details>

<details>
<summary><strong>4. Tag-Based Filtering & Categories</strong></summary>

- Filter posts by difficulty: Beginner / Intermediate / Advanced
- Filter by topic: CV, NLP, RL, Systems, Theory
- Tag-based navigation UI

</details>

<details>
<summary><strong>5. Reading Time Estimation</strong></summary>

- Auto-calculate reading time from word count
- Display alongside post metadata

</details>

---

### Getting Started

**1. Fork & Clone**

```bash
git clone https://github.com/<your-username>/mlmondays.git
cd mlmondays
```

**2. Install & Run**

```bash
npm install
npm run dev
```

**3. Create a Branch**

```bash
git checkout -b feature/your-feature-name
```

**4. Commit & Push**

```bash
git add .
git commit -m "feat: add keyword slug generation"
git push origin feature/your-feature-name
```

**5.** Open a Pull Request to `main`.

---

## Writing a Blog Post

1. Create a new `.md` file inside the `posts` directory.
2. Add frontmatter with all required fields.
3. Use clear headings and structured formatting.
4. Keep writing intuitive and implementation-focused.

**Frontmatter Template:**

```yaml
---
title: "Understanding Transformers from First Principles"
description: "An intuitive deep dive into attention mechanisms."
date: "2026-02-01"
author: "Your Name"
tags: ["NLP", "Transformers", "Deep Learning"]
slug: "understanding-transformers-first-principles"
---
```

---

## Our Ethos

> *ML Mondays is not about publishing for volume. It's about publishing for clarity.*

- Break down intimidating topics
- Encourage technical depth
- Build strong ML intuition
- Document learning publicly

If you care about understanding AI deeply and communicating it clearly — this space is for you.

---

<div align="center">

**NeuralHive** — AI/ML Club, PES University EC Campus

*Built by students. For students.*

</div>

