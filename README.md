# Simple_xG

ggplot(data) +
geom_bar(aes(x = Location, y = Conversion, fill = Location), stat = ‘identity’, show.legend = FALSE) +
labs(y = ‘Conversion (%)’, x = ‘Shot Location’, title = ‘Figure 1’, subtitle = ‘Conversion Rate by Shot Type’) +
geom_text(aes(label=Conversion, x = Location, y = Conversion), vjust = -.2) +
theme_bw()
