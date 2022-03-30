notes from stack overflow

## Jupyter Notebook

#### Tables 
The first row of the table defines the headers, then the next row defines the alignment of each column. You duplicated the alignment at the top of the table and where it's actually supposed to go.

The right Markdown should simply be what you have in your syntax, but remove the first row:
```
| Stretch/Untouched | ProbDistribution | Accuracy |
| --- | --- | --- |
| Stretched | Gaussian | .843 |
```

| Stretch/Untouched | ProbDistribution | Accuracy |
| --- | --- | --- |
| Stretched | Gaussian | .843 |

credit: [rayryeng](https://stackoverflow.com/users/3250829/rayryeng)
