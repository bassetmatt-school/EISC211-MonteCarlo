 # EISC 211 : Monte Carlo

## Important

Has to be finish by 4/17/2022
a

## Possible problems with `mpstyles.py`

It may cause various issues, due to LaTeX support mainly

### Solution 1 :
Remove the following lines or comment them in the first block code :

```python
import mpstyle
mpstyle.mpSetParamStyle("code")
```

### Solution 2 :
Install all the needed packages for it to work :

1. Install texlive or any LaTeX compiler, should look like this (on Arch), adapt with each distro <br>
Windows = glhf
```bash
sudo pacman -S texlive-core texlive-latexextra
```

2. Make sure dvipng is installed, typically by taping `dvipng` in a terminal 
3. Install LaTeX for python 
```bash
pip install latex
```

4. Isokay