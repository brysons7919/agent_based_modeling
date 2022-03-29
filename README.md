# agent_based_modeling

This repo will include Jupyter notebooks for visualizing and analyzing output from agent based simulations run using the iDynoMICS platform:

    Lardon, Laurent A., Brian V. Merkey, Sónia Martins, Andreas Dötsch, Cristian Picioreanu, Jan-Ulrich Kreft, and Barth F. Smets. 2011. “iDynoMiCS: Next-Generation Individual-Based Modelling of Biofilms.” Environmental Microbiology 13 (9): 2416–34.
    
The simulations generate xml files with information about the Agents and the Environment over time. Additionally the software outputs a 2 or 3D rendering of the simulation using POV-Ray. The code presented here converts the image format to be used easily with python for making gifs or mp4s and compiles the time series data from the xml files into figures and animations. Some example animations follow:

## Biofilm gif

![SegmentLocal](./img/v4.02.gif "biofilm")

## Vertical profile of Agent growth rates

![SegmentLocal](./img/v402.env_state.AO1gNH4ox-rate.AO3gNH4ox-rate.AO5gNH4ox-rate.AO7gNH4ox-rate.AO9gNH4ox-rate.AMXgrowthNH4ox-rate.gif "NH4 ox rate")


## Vertical profile of Agent biomass distribution

![SegmentLocal](./img/v402.env_state.AO1.AO3.AO5.AO7.AO9.AMX.gif "env state")