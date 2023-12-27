## 📄 Resumé – Alexis Vielma

> The most up-to-date version of my resumé.

You can download the resumé from the latest release [here](https://github.com/aelxxs/resume/releases/download/Resume/resume.pdf).

Or view it online [here](https://alexis.lol/resume.pdf).

### Tools used

-   [LaTeX](https://www.latex-project.org/)
-   [GitHub Actions](https://github.com/features/actions)

### Usage

> Want to use this as a template for your own resumé? Follow these steps:

```bash
git clone git@github.com:aelxxs/resume.git
cd resume
```

Then, update the `src/resume.tex` file with your own information. If you want to view changes you've made, run the following command:

```bash
pdflatex src/resume.tex
```

or use [overleaf](https://www.overleaf.com/) to edit and view changes in real time.

Once you're finished making changes, you can push them to GitHub and it will automatically build the resumé and upload it to the latest release.

```bash
git add .
git commit -m "feat: update resume"
git push
```

### CI

The CI script is located in `.github/workflows/tex-to-pdf.yml` or you can view it [here](https://github.com/aelxxs/resume/blob/main/.github/workflows/tex-to-pdf.yml)

### Contributing

Don't. This is my resumé, but if you want to use it as a template for your own resumé, feel free to fork it and make changes to your own copy.

If you find a typo or something, feel free to open an issue or submit a pull request.

Otherwise, if you have any suggestions for improvements, feel free to open an issue or submit a pull request. I'm always looking for ways to improve my resumé!

### Acknowledgements

I can't remember where I got the original template from, but I've made a lot of changes to it since then.

### License

Distributed under the MIT License. See `LICENSE` for more information.
