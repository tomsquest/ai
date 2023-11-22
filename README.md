# AI Experiments

Welcome to my experiments and projects around AI, Deep-Learning and LLM.

## This site setup

This site is hosted on GitHub Pages as a Jekyll-generated website.
After a push, GitHub will rebuild the site at https://ai.tomsquest.com.

```bash
# Dependencies
# See: https://github.com/rbenv/ruby-build/wiki#ubuntudebianmint
$ apt-get install autoconf patch build-essential rustc libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libgmp-dev libncurses5-dev libffi-dev libgdbm6 libgdbm-dev libdb-dev uuid-dev

$ asdf install $(cat .tool-versions)

$ bundle install

$ bundle exec jekyll serve --livereload
```