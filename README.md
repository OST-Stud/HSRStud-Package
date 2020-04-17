# HSR-Stud LaTeX Style & Macros

## TODO
- [X] Notation Macros
  - [X] Vectors, Matrices and Tensors
  - [X] Equalities
  - [X] Derivatives and vector operators
- [X] HSR Colors
- [ ] Document classes
  - [ ] Summary
  - [ ] Long summary
  - [ ] Short document
- [ ] Documentation on how to contribute
- [ ] More options (suggestions?)

## Compile
It is as simple as it gets. 
This will generate a `hsrstud.sty` file that can be placed in any folder other LaTeX project,
which can access the library with `\usepackage{hsrstud}`
```
$ xelatex hsrstud.dtx
```

## Documentation
The usage of the macros is documented in `hsrstud.pdf`, which is automatically generated when
the `dtx` file is compiled.

## Contribute (WIP)
### Add a new macro
```latex
%    \begin{macro}{\piggy}
%    Here I explain what my macro does, for example it takes one optional
%    argument \oarg{carrot} and a required argument \marg{tomato}
%
%    \begin{macrocode}
\newcommand{\piggy}{%
    ... your code
}
%    \end{macrocode}
%    \end{macro}
```
### Add a new option
### Pitfalls

## License
```
HSR-Stud-Style (c) by Naoki Pross

HSR-Stud-Style is licensed under a Creative Commons Attribution-ShareAlike 4.0 Unported License.
You should have received a copy of the license along with this work. If not, see

http://creativecommons.org/licenses/by-sa/4.0/
```
