# Getting Started
This repository contains R scripts for modeling and analyzing dose-response relationships using both the approximate beta-Poisson and exponential models. 
These scripts are designed to be flexible and can be adapted to various datasets and research needs.
### Dependencies
- R programming language
- R packages: `stats4`, `ggplot2`, `boot`
Make sure you have R installed on your system along with the necessary packages. You can install the packages using the following commands in R:
```R
install.packages("stats4")
install.packages("ggplot2")
install.packages("boot")
```
### Installation

Clone the repository to your local machine:

```
git clone https://github.com/[your-username]/[your-repository-name].git
```
### Data Preparation

Before running the models, prepare your dataset according to the following structure:

- `dose`: A vector of doses (numeric).
- `total`: The total number of hosts at each dose level (numeric).
- `infected`: The number of infected hosts at each dose level (numeric).

Example:
```R
dose <- c(10, 50, 100, 500)
total <- c(20, 20, 20, 20)
infected <- c(2, 5, 10, 15)
```
## Usage

Replace the example data in the script with your dataset. The main functions and analyses are documented within the scripts. Follow the comments for guidance on running the models and interpreting the results.

### Running the Scripts

Open the R scripts in your R environment and run them as normal R scripts.




















