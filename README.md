How to Use Math Formulas in GitHub Markdown Documents
====

[comment]: # ( Taken from: https://stackoverflow.com/a/47798853/1474291 )

![\sum_{\forall i}{x_i^{2}}](https://latex.codecogs.com/svg.latex?%5Csum_%7B%5Cforall+i%7D%7Bx_i%5E%7B2%7D%7D)

The Project Structure
----

```
 |
 +-- Math
 |    |
 |    +-- Formula.math
 |         ...    
 |
 +-- README.md
      ...
        
```

The Source
----

* [Math/Formula.math][1]

[1]: https://github.com/Zingam/Math-in-Markdown/blob/master/Math/Formula.math

*LaTeX* source:

```LaTex
\sum_{\forall i}{x_i^{2}}
```

The Link
----

1. CodeCogs's URL:
    * https://latex.codecogs.com/svg.latex?
2. Write the formula in *LaTeX*: `\sum_{\forall i}{x_i^{2}}`.

Option ***A***:

3. Get the URL from: https://www.codecogs.com/latex/eqneditor.php

Option ***B***:

3. Convert the formula to percent-encoded string.
4. Combine the CodeCogs's URL and encoded formula string:
    * https://latex.codecogs.com/svg.latex?%5Csum_%7B%5Cforall+i%7D%7Bx_i%5E%7B2%7D%7D

The Markdown
----

```
![\sum_{\forall i}{x_i^{2}}](https://latex.codecogs.com/svg.latex?%5Csum_%7B%5Cforall+i%7D%7Bx_i%5E%7B2%7D%7D)
```

The Math Formula
----

* Standard:

```LaTeX
\sum_{\forall i}{x_i^{2}}
```

![\sum_{\forall i}{x_i^{2}}](https://latex.codecogs.com/svg.latex?%5Csum_%7B%5Cforall+i%7D%7Bx_i%5E%7B2%7D%7D)

* Multiline formula:

```LaTeX
\newline
2 + 2 = 4 \newline
2 + 3 = 5 \newline
\frac{2}{4} = 0.5
```

![\newline
2 + 2 = 4 \newline
2 + 3 = 5 \newline
\frac{2}{4} = 0.5](https://latex.codecogs.com/svg.latex?\inline&space;\newline&space;2&space;&plus;&space;2&space;=&space;4&space;\newline&space;2&space;&plus;&space;3&space;=&space;5&space;\newline&space;\frac{2}{4}&space;=&space;0.5)
