### Text and annotation related

Annotate outside of plot and underline text

See https://stackoverflow.com/questions/46309675/ggplot2-in-r-annotate-outside-of-plot-and-underline-text

Don't clip text outside of plot panel
```
ggplot(...) + coord_cartesian(clip = 'off')
```

Change legend font size and number of columns
```
guides(color = guide_legend(override.aes = list(size = 2), ncol = 2))
```
