**BifurcationKit Tutorial: Jansen-Rit Neural Mass Model**

A step-by-step tutorial for performing bifurcation analysis of the Jansen-Rit neural mass model using BifurcationKit.jl in Julia.  

**Overview**

The purpose of this notebook is to guide you through how to use BifurcationKit to study the Jansen-Rit model. The aim of this tutorial is to reproduce Figures 22 and 24 in the paper by Grimbert and Faugueras. The Jansen-Rit model is a widely used neural mass model that describes the dynamics of a cortical column through the interaction of excitatory and inhibitory neural populations. This tutorial demonstrates how to use BifurcationKit to systematically characterise the model's dynamical regimes — including stable fixed points, oscillatory states, and the transitions between them.  

**Contents**

-Setting up the Jansen-Rit model in Julia  
-Computing equilibria and their stability  
-Performing continuation to trace solution branches  
-Identifying bifurcation points (saddle-node, Hopf)  
-Visualising bifurcation diagrams  

**Requirements**

-Julia 1.x  
-BifurcationKit.jl  
-Plots. 

**Background**

This tutorial was developed as part of an MSc thesis on laminar neural mass model validation within the Neurotwin consortium, which aims to build personalised virtual brain models for optimising transcranial electrical stimulation in Alzheimer's disease.
Usage
Open jansen-rit-tutorial.ipynb in Jupyter with a Julia kernel, or use VS Code with the Julia extension.
