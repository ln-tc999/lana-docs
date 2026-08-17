---
seo:
  title: Lanadev — Muhammad Maulana Firdaussyah
  description: Documentation and Blog of Lanadev (Muhammad Maulana Firdaussyah), Fullstack Web Developer.
---



::u-page-hero{class="bg-white dark:bg-[#0a0a0a] border-b border-gray-200 dark:border-gray-800"}
---
orientation: horizontal
---
#top
:hero-background

#title
Lanadev [Knowledge Base]{.text-zinc-500} & Blog

#description
Explore my technical documentation, setup guides, and thoughts on web development. Built with Nuxt, tailored for speed and simplicity.

#links
  :::u-button
  ---
  to: /getting-started
  size: xl
  trailing-icon: i-lucide-arrow-right
  color: black
  ---
  Explore Docs
  :::

  :::u-button
  ---
  icon: i-lucide-book-open
  color: neutral
  variant: outline
  size: xl
  to: /blog
  ---
  Read the Blog
  :::

#default
  :::prose-pre
  ---
  code: |
    # Initialize a new project
    npx nuxi@latest init my-project
    cd my-project

    # Install dependencies
    pnpm install

    # Start development server
    pnpm dev
  filename: terminal
  icon: i-lucide-terminal
  ---

  ```bash [terminal]
  # Initialize a new project
  npx nuxi@latest init my-project
  cd my-project

  # Install dependencies
  pnpm install

  # Start development server
  pnpm dev
  ```
  :::
::

::u-page-section{class="bg-white dark:bg-[#0a0a0a] border-b border-gray-200 dark:border-gray-800"}
#title
Explore by Category

#description
Dive into my technical resources, organized by topics to help you find exactly what you need.

#features
  :::u-page-feature
  ---
  icon: i-lucide-play-circle
  to: /getting-started
  ---
  #title
  Getting Started
  #description
  Quick start guides, installation instructions, and essential concepts to kick off your projects.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-box
  to: /essentials
  ---
  #title
  Essentials
  #description
  Core concepts, components, and Markdown features available in this documentation site.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-layout-template
  to: /templates
  ---
  #title
  Templates & Boilerplates
  #description
  Pre-configured setups for React, Next.js, and more to accelerate your development workflow.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-book-open
  to: /blog
  ---
  #title
  Tech Blog
  #description
  Articles on fullstack development, AI engineering, system architecture, and tech tutorials.
  :::
::

::u-page-section{class="bg-white dark:bg-[#0a0a0a] border-b border-gray-200 dark:border-gray-800"}
#title
Recent Articles
#description
Latest insights and updates from my development journey.

#features
  :::u-page-feature
  ---
  icon: i-lucide-file-text
  to: /blog
  ---
  #title
  Welcome to Lanadev Blog
  #description
  A quick introduction to what you can expect from this knowledge base.
  :::
  
  :::u-page-feature
  ---
  icon: i-lucide-file-text
  to: /blog
  ---
  #title
  Building a Brutalist Portfolio
  #description
  Insights and design decisions from building a high-performance Next.js portfolio.
  :::
::

::u-page-section{class="bg-white dark:bg-[#0a0a0a]"}
  :::u-page-c-t-a
  ---
  links:
    - label: Read the Blog
      to: '/blog'
      trailingIcon: i-lucide-arrow-right
      color: black
    - label: View on GitHub
      to: 'https://github.com/maulana-tech'
      target: _blank
      variant: outline
      color: neutral
      icon: i-simple-icons-github
  title: Stay Updated
  description: Join me as I share more open-source templates, tech tutorials, and development tips.
  class: dark:bg-[#0a0a0a] border border-gray-200 dark:border-gray-800
  ---
  :::
::
