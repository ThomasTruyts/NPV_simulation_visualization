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

P&L data is imported, with each column a cost or revenue and each row a period in time. THIS IS DUMMY DATA.

## Methodology

The notebook employs a Gaussian distribution to model the uncertainty in P&L data. It generates multiple simulations of cash flows, calculates the NPV for each simulation, and aggregates the results to create a distribution of NPV values. Skewness and heteroscedasticity are taken into account to improve the realism of the simulations.

## Results

The project generates informative visualizations and statistical summaries to provide insights into the NPV uncertainty. You will find visual representations of the NPV distribution, including mean, standard deviation, and percentiles.

Here some of the simulations of variables:
![Picture 1](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/8818f708-7d72-483b-90d7-87e99eec0d18)
![Picture 2](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/b8e81c3f-1c5f-4c45-bb3c-f12fcd63396c)
![Picture 3](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/c98c0003-77e2-4816-9e3b-a72af867cd4e)
![Picture 4](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/f7d8d6cc-2707-4b83-8198-7bf192c2bbb9)
![Picture 5](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/499b6d67-c016-4496-a582-81ed7bf9cf9d)
![Picture 6](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/9e375141-0bff-416c-a295-bd0bafe52bd5)
![Picture 7](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/bfc1c099-b126-45a0-9793-cccc91c22430)
![Picture 8](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/0be92354-a0f2-45a6-a707-e73582d30ec8)
![Picture 9](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/bbf10bc3-a3e1-4adb-b6d6-4d9822bd6091)
![Picture 10](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/67aefa8f-add6-4c09-9563-20781adb85aa)

## Sensitivity Analysis

The sensitivity analysis section of the notebook evaluates the sensitivity of NPV to changes in each P&L statement. It helps identify which factors have the most significant impact on NPV.
![sens](https://github.com/ThomasTruyts/NPV_simulation_visualization/assets/104683599/7d9db5e9-4297-4d26-ba5b-23688d7ec043)

## Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.
