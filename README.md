# Repo-Card
:sunglasses: showcase :octocat: repositories on your website :metal:!

## Demo
Light theme
<img src="https://github.com/Tarptaeya/repo-card/blob/master/light-default.png" width=410></img>

Dark theme
<img src="https://github.com/Tarptaeya/repo-card/blob/master/dark-default.png" width=410></img>

For a live demo, visit [https://tarptaeya.github.io/repo-card](https://tarptaeya.github.io/repo-card).

## Usage
```
<!-- head -->
<script src="https://tarptaeya.github.io/repo-card/repo-card.js"></script>


<!-- inside body, where you want to create the card -->
<div class="repo-card" data-repo="username/repository"></div>

<!-- NEW: for dark theme just set data-theme attribute -->
<div class="repo-card" data-repo="username/repository" data-theme="dark-theme"></div>
```

## Features
- Supports dark theme
- Supports GitHub emojis
- Supports language colors
- Hides stars and forks when their count is 0.
- Shows the source repository in case of fork.
- Creates card similar to GitHub pinned repository's style

### Related Projects

- [thislooksfun/svelte-repo-card](https://github.com/thislooksfun/svelte-repo-card)

### Thanks
- [ozh/github-colors](https://github.com/ozh/github-colors) for providing GitHub colors for all the languages.
