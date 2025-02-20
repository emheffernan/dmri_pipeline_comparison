# dmri_pipeline_comparison

This repository contains some results from when I compared two open-source preprocessing pipelines to see how well they handle motion in kids' diffusion MRI (dMRI) data. 

Diffusion MRI measures how water molecules move in someone's brain. This information can be used to trace out white matter pathways (neural circuitry). dMRI is really sensitive to motion artifacts – if someone moves their head during a scan, it negatively impacts data quality. Controlling for the effects of motion is especially important in people prone to motion, like kids. 

Here I compare two dMRI preprocessing pipelines to see how well they can eliminate motion in a pediatric dMRI dataset. My analysis is summarized in the op_notebook.nb.html 
file (view the rendered version [here](https://rawcdn.githack.com/emheffernan/dmri_pipeline_comparison/7a1cb0108fc1ba0733c30db2411298dc092ccd6b/op_notebook.nb.html)), and the pdf file is poster I made to visualize my methods and results. 
