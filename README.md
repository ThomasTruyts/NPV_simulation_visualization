# Project Name: NPV Uncertainty Analysis

## Overview

This repository contains a Jupyter Notebook that performs a detailed analysis of Net Present Value (NPV) uncertainty. The analysis is based on generating simulations using the Gaussian distribution, taking into account skewness and heteroscedasticity. These simulations are used to calculate a distribution of NPV values. Additionally, a sensitivity analysis is performed to visualize the impact of each Profit and Loss (P&L) statement on the NPV value. The primary goal of this project is to provide insights into the uncertainty surrounding NPV estimations.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Sensitivity Analysis](#sensitivity-analysis)
- [Contributing](#contributing)

## Introduction

Net Present Value (NPV) is a critical financial metric used to evaluate the profitability of an investment or project. However, NPV calculations often rely on various assumptions, making it susceptible to uncertainty. This project aims to address this uncertainty by simulating NPV values based on P&L data, incorporating the Gaussian distribution with skewness and heteroscedasticity.

## Features

- Generates simulations of NPV values based on P&L data.
- Accounts for skewness and heteroscedasticity in the simulations.
- Calculates a distribution of NPV values.
- Conducts sensitivity analysis to assess the impact of each P&L statement on NPV.

## Usage

To use this project, follow these steps:

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook included in the repository.
3. Input your P&L data and adjust simulation parameters as needed.
4. Run the notebook to generate NPV simulations and sensitivity analysis.

## Installation

To run the notebook, you need the following dependencies:

- NumPy
- SciPy
- Matplotlib
- Pandas

## Data

P&L data is imported, with each column a cost or revenue and each row a period in time.

## Methodology

The notebook employs a Gaussian distribution to model the uncertainty in P&L data. It generates multiple simulations of cash flows, calculates the NPV for each simulation, and aggregates the results to create a distribution of NPV values. Skewness and heteroscedasticity are taken into account to improve the realism of the simulations.

## Results

The project generates informative visualizations and statistical summaries to provide insights into the NPV uncertainty. You will find visual representations of the NPV distribution, including mean, standard deviation, and percentiles.

## Sensitivity Analysis

The sensitivity analysis section of the notebook evaluates the sensitivity of NPV to changes in each P&L statement. It helps identify which factors have the most significant impact on NPV.

## Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.
