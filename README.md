# Alex Waibel's Personal Website
This is the repository for my personal website, including some blog posts. The site is written in [Jekyll](https://github.com/jekyll/jekyll), using the [Minimal Mistakes theme](https://github.com/mmistakes/minimal-mistakes) and served using [GitHub Pages](https://pages.github.com/).


## Running the project
The easiest way to start this project is to use VS Code and docker to deploy the devcontainer either on GitHub Codespaces or locally. You'll need to use the following in the container's terminal to see the jekyll logs:
```bash
tail -f nohup.out
```

Otherwise if you don't want to use docker you can follow [this guide](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) to run it locally.