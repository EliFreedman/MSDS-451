# Programming Assignment 1

Author: Eli Freedman<br>
Course: MSDS 451: Financial Engineering<br>
Date: October 5, 2025

## Overview

This programming assignment tasks developing a machine learning model to predict whether a stock, ETF, commodity, or other asset price will trend up or down the following day. To successfully accomplish this, feature engineering, feature selection, and cross-validation may be employed in order to develop a comprehensive model.

For my variation of this project, I decided to focus on $BHP, a mining and metals company based out of Australia.

## Structure

`README.md`: Contains all information required to understand and run this assignment<br>
`requirements.txt`: All Python modules used in this assignment<br>
`programming_assignment_1.ipynb`: Code used to develop the predictive model<br>
`programming_assignment_1.html`: HTML version of the notebook (better viewing)<br>
`bhp_historical_data.csv`: Historical data of the $BHP ticker from 2000-2025<br>
`bhp-with-computed-features.csv`: $BHP ticker data with additional engineered features

## Set Up

1. Ensure you are running Python 3.12 or later. This project was developed using 3.12, so it may not be compatible with previous versions.
2. Create a virtual environment by executing `python -m venv .venv`
3. Enter the virtual environment
4. Download the requirements by executing `pip -r requirements.txt`
5. Run all cells in the `programming_assignment_1.ipynb` notebook

## AI Usage

This assignment utilized ChatGPT as a resource for development. It was useful to reference while exploring the Polars package.

AI was also utilized for stock research. Below is an example of one query/answer pair used in this assignment.

Query: Write me a description of Broken Hill Proprietary Company including a short history.

Answer: The Broken Hill Proprietary Company Limited, commonly known as BHP, was founded in 1885 in Broken Hill, New South Wales, after the discovery of one of the world’s richest silver, lead, and zinc deposits. Originally established as a mining company, BHP quickly grew into a major player in Australia’s industrial development, expanding into steel production in the early 20th century with operations in Newcastle and later Whyalla and Port Kembla. Over time, the company diversified into coal, petroleum, iron ore, and copper, becoming one of the world’s largest resource companies. In 2001, BHP merged with the Anglo-Dutch mining company Billiton, forming BHP Billiton, before simplifying its name back to BHP in 2017. Today, BHP is a global leader in natural resources, headquartered in Melbourne, Australia, with operations across multiple continents.