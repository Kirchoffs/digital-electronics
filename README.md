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