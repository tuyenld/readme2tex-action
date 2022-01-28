# readme2tex-action
Github action rendering LaTeX `*.tex.md` file for Github Readmes `*.md`.

# How to use
- Add [action.yml](.github/workflows/action.yml) file to your repo at `.github/workflows/action.yml`.
- Change branch name `main` if it is necessary.
```yml
on:
  push:
    branches: [main]
  pull_request:
    branches: [main]
```

# How does it look like?
Here is Latex.
<p align="center"><img src="svgs/d27ecd9d6334c7a020001926c8000801.svg?invert_in_darkmode" align=middle width=160.1989356pt height=31.014203549999998pt/></p>
Block math looks great.
<p align="center"><img src="svgs/32737e0a8d5a4cf32ba3ab1b74902ab7.svg?invert_in_darkmode" align=middle width=127.9847844pt height=39.452455349999994pt/></p>

It is inline math. If <img src="svgs/15b9e78f3a7cb11ea59b95c9553fb928.svg?invert_in_darkmode" align=middle width=119.34141284999998pt height=26.76175259999998pt/>, then <img src="svgs/2b1f70f6a49aea806b0a5f021e843447.svg?invert_in_darkmode" align=middle width=112.44128444999998pt height=33.20539200000001pt/>.

See more at [readme2tex](https://github.com/leegao/readme2tex)