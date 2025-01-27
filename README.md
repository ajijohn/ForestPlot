# ForestPlot

The ForestPlot R package is designed to facilitate the cleaning, analysis and
visualization of rectangular mapped forest plot data.

When a rectangular mapped forest plot is constructed, the size, species identity
and location of each tree meeting a specified minimum size threshold is 
recorded. Plots are typically re-censused periodically to document mortality,
re-measure tagged trees, and record trees that have reached the minimum size
threshold since the previous census. Together, these data allow us to
quantitatively describe the local neighborhood of any tree or specified location
in the plot. These neighborhood descriptions can then be used as informative
covariates of forest processes, such as tree growth, tree mortality, and 
spatial variation in soil microbial communities.

Massaging these invaluable datasets into a format conducive to exploration and
analysis is no small feat. First, we need to extract data on all the trees
growing in each of several thousand focal trees' neighborhoods. Then we may
want to calculate the annual growth rate of each tree using its repeated size
measurements. We may also want to generate gps locations for individual trees
in order to connect them with spatially explicit data sources such as 
topographical data. Typically, each research group working with mapped forest
plot data must complete these arduous coding tasks independently. ForestPlot
attempts to negate this time-consuming process by providing flexible functions
that can perform each of these tasks on any mapped forest plot dataset.

## Installation

```
# Install devtools package if not already installed
install.packages("devtools")

# Use devtools to install ForestPlot
devtools::install_github("sgraham9319/ForestPlot")
```

## Updates

The functions of ForestPlot handle only the most common analytical tasks
associated with mapped forest plot data. If you encounter a task that is not
covered by ForestPlot, please feel free to build that functionality and submit
a pull request, or contact us if you're not sure where to start.
