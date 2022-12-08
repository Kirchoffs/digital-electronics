# digital-electronics

## Latex Notes
### Put a bar or a tilde over a letter
```
\tilde{x}
\bar{x}
\overline{x}
```

### Math equation
```
\begin{equation*}
    x + y = z
\end{equation*}
```
or
```
$$
    x + y = z
$$
```
or
```
\begin{align*}
    x + y = z
\end{align*}
```
or if you want to align all the equations to the left of the page:
```
\usepackage[fleqn]{amsmath}

\begin{flalign*}
    x + y = z
\end{flalign*}
```

### Space
Small space: `\,`  
Medium space: `\:`  
Big Space: `\;`

### Environment
1\. __flalign__  
flalign is a LaTeX environment that is used to align equations or text in a specified way. It is a variation of the align environment, but with different alignment options. flalign is part of the amsmath package and provides more control over how the equations are displayed and aligned.