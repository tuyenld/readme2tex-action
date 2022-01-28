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
$$
\huge\text{Hello \LaTeX}
$$
Block math looks great.
$$
\frac{n!}{k!(n-k)!} = {n \choose k}
$$

It is inline math. If $ax^2 + bx + c = 0$, then $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$.

See more at [readme2tex](https://github.com/leegao/readme2tex)