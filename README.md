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

<!-- for dark theme just set data-theme attribute -->
<div class="repo-card" data-repo="username/repository" data-theme="dark-theme"></div>

<!-- optional tag attributes to customize displayed name and description -->
<!-- if omitted, default to data retrieved from GH -->
<div class="repo-card" data-repo="username/repository" data-display-name="A Nicer Name" data-description="My description"></div>
```

## Features
- Cache response to handle GitHub API rate limits (**NEW**)
- Supports dark theme
- Supports GitHub emojis
- Supports language colors
- Hides stars and forks when their count is 0.
- Shows the source repository in case of fork.
- Creates card similar to GitHub pinned repository's style
- Element classes to expose components to external styling (CSS, Less, SCSS, ecc...)
	- `.repo-card-background`
	- `.repo-card-name`
	- `.repo-card-icon`
	- `.repo-card-fork-origin`
	- `.repo-card-description`
	- `.repo-card-language`
	- `.repo-card-starred-count`
	- `.repo-card-forks-count`

### Related Projects

- [thislooksfun/svelte-repo-card](https://github.com/thislooksfun/svelte-repo-card)

### Thanks
- [ozh/github-colors](https://github.com/ozh/github-colors) for providing GitHub colors for all the languages.
