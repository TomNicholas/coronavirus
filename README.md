# Coronavirus: The Simplest Model

While the models used by actual epidemiologists can be complex, the essential dynamics of the spread of the novel coronavirus can be captured by models which are suprisingly simple.

This repo contains a description of the simplest possible model of influenza-like disease spread (the SIRD model), and adds complexities to it to reproduce predictions from current major headlines.

For example, a simple extension to the initial model can demonstrate that increasing the effectiveness of social distancing (Q) reduces the mortality rate by reducing strain on healthcare systems.

![Effect-of-flattening-the-infection-curve](https://github.com/TomNicholas/coronavirus/blob/master/flatten-the-curve.png)


The equations, code, results and explanations are all in [the notebook](https://github.com/TomNicholas/coronavirus/blob/master/covid-19_model.ipynb).




### To-Do:

- Adaptive triggering of suppression strategies (see Figure 4 of [Imperial College report](https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf?fbclid=IwAR1j0zcv_htn0A6OHNGhDkV5Facsz_jLVJxYtel7MEl1b7VvBsPgnkcXMAM))
