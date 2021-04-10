# jarombek-com-posts

### Overview

HTML (JSX) files displayed as articles on `jarombek.com`.

### Commands

**Tokenize an HTML/JSX file as JSON (MacOS)**

```bash
# Perform these commands from inside the html-tokenizer repository
cd ~/<repos-root>/html-tokenizer

# One time setup
nvm use v10.15.3
npm install -g

tokenize ../jarombek-com-posts/<year>/<filename>.html -o parsed.json
```
