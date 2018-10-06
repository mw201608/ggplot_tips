### Legend related
Change the legend location and the spacing between legend and the panel
```
theme(legend.position="top", legend.justification="right", legend.margin=margin(t=0,r=0,b=0,l=0),
  legend.box.margin=margin(t=0,r=0,b=0,l=-5)
```
See https://stackoverflow.com/questions/41362895/r-ggplot2-change-the-spacing-between-the-legend-and-the-panel

Change the legend key size
```
theme(legend.key.size=unit(0.5,"line"))
```
Change legend title for fill
```
labs(fill=..)
```
