# investing-101
This repo contains the contents of an introductory presentation about (index) investing. The presentation has been created with the Beamer Latex class. Latex has a reputation for being complex, but for lazy text heavy markdown based presentations it's quite good.

## instructions
In a debian based distribution you need to install some packages using

```
apt-get install pandoc texlive-latex-base texlive-fonts-recommended texlive-fonts-extra
```

and you can convert the md to pdf as follows

```
pandoc investing-101.md -t beamer -o pdf/devoxx-gr-2025-investing-101-for-geeks.pdf
```