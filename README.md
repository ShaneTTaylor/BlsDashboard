
## Bureau of Labor Statistics Employment Dashboard

Created by Shane Taylor

August 2022

## Summary Description

This project retrieves employment data from the Bureau of Labor Statistics API and creates a slide deck of plots.

The R Markdown file `bls_dashboard.Rmd` creates a function that sends a set of requests to the BLS API, receives a JSON response, and returns a single data frame. This file also creates a function that takes a request for data across a number of years and breaks it into a subset of requests, because the API limits requests to no more than 20 years of data. Finally, it plots several charts and presents them as a slideshow.

