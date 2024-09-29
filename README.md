
<!-- Edit README.md, not index.md -->

# Da Vinci pair programming in your terminal

Da Vinci - lets you pair program with LLMs,
to edit code in your system, github, and applications
Start a new project or work with an existing git repo.

[connect to almost any LLM](https://aider.chat/docs/llms.html).

<!-- SCREENCAST START -->
<p align="center">
  <img
    src="https://aider.chat/assets/screencast.svg"
    alt="aider screencast"
  >
</p>
<!-- SCREENCAST END -->

<!-- VIDEO START
<p align="center">
  <video style="max-width: 100%; height: auto;" autoplay loop muted playsinline>
    <source src="/assets/shell-cmds-small.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>
VIDEO END -->

<p align="center">
  <a href="https://discord.gg/Tv2uQnR88V">
    <img src="https://img.shields.io/badge/Join-Discord-blue.svg"/>
  </a>
  <a href="https://aider.chat/docs/install.html">
    <img src="https://img.shields.io/badge/Read-Docs-green.svg"/>
  </a>
</p>

## Getting started
<!--[[[cog
# We can't "include" here.
# Because this page is rendered by GitHub as the repo README
cog.out(open("aider/website/_includes/get-started.md").read())
]]]-->

You can get started quickly like this:

```
python -m pip install -U aider-chat

# Change directory into a git repo
cd /to/your/git/repo

# Work with Claude 3.5 Sonnet on your repo
export ANTHROPIC_API_KEY=your-key-goes-here
aider

# Work with GPT-4o on your repo
export OPENAI_API_KEY=your-key-goes-here
aider 
```
<!--[[[end]]]-->

See the
[installation instructions](https://aider.chat/docs/install.html)
and other
[documentation](https://aider.chat/docs/usage.html)
for more details.

## Features

- Run aider with the files you want to edit: `aider <file1> <file2> ...`
- Ask for changes:
  - Add new features or test cases.
  - Describe a bug.
  - Paste in an error message or or GitHub issue URL.
  - Refactor code.
  - Update docs.
- Aider will edit your files to complete your request.
- Aider [automatically git commits](https://aider.chat/docs/git.html) changes with a sensible commit message.
- Aider works with [most popular languages](https://aider.chat/docs/languages.html): python, javascript, typescript, php, html, css, and more...
- Aider works best with GPT-4o & Claude 3.5 Sonnet and can [connect to almost any LLM](https://aider.chat/docs/llms.html).
- Aider can edit multiple files at once for complex requests.
- Aider uses a [map of your entire git repo](https://aider.chat/docs/repomap.html), which helps it work well in larger codebases.
- Edit files in your editor while chatting with aider,
and it will always use the latest version.
Pair program with AI.
- [Add images to the chat](https://aider.chat/docs/usage/images-urls.html) (GPT-4o, Claude 3.5 Sonnet, etc).
- [Add URLs to the chat](https://aider.chat/docs/usage/images-urls.html) and aider will read their content.
- [Code with your voice](https://aider.chat/docs/usage/voice.html).


## Top tier performance

[Aider has one of the top scores on SWE Bench](https://aider.chat/2024/06/02/main-swe-bench.html).
SWE Bench is a challenging software engineering benchmark where aider
solved *real* GitHub issues from popular open source
projects like django, scikitlearn, matplotlib, etc.

## More info

- [Documentation](https://aider.chat/)
- [Installation](https://aider.chat/docs/install.html)
- [Usage](https://aider.chat/docs/usage.html)
- [Tutorial videos](https://aider.chat/docs/usage/tutorials.html)
- [Connecting to LLMs](https://aider.chat/docs/llms.html)
- [Configuration](https://aider.chat/docs/config.html)
- [Troubleshooting](https://aider.chat/docs/troubleshooting.html)
- [LLM Leaderboards](https://aider.chat/docs/leaderboards/)
- [GitHub](https://github.com/paul-gauthier/aider)
- [Discord](https://discord.gg/Tv2uQnR88V)
- [Blog](https://aider.chat/blog/)
