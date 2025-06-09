## Monte Carlo Simulation: revisiting Buffon's needles

This project offers a fresh perspective on the classical Buffon's needles experiment by incorporating directional biases in the needle orientation. Using Python and popular scientific libraries, it simulates the experiment, analyzes statistical confidence, and explores how orientation noise influences the estimation of π and other irrational numbers.

The simulation is implemented in a Jupyter Notebook ([montecarlo_simulation.ipynb](montecarlo_simulation.ipynb)) using Python and  the most popular scientific libraries.

## Features

- **Buffon's needles simulation:**  
  Estimate the value of π by simulating random needle throws on a lined sheet.

- **Statistical Analysis:**  
  Calculate confidence intervals for the π estimation using the central limit theorem and visualize the distribution of sample means.

- **Oriented Needles Experiment:**  
  Simulate scenarios where needles are not randomly oriented, but follow a preferred direction (e.g., due to a magnetic field), and analyze how this affects crossing probabilities.

- **Theoretical Comparison:**  
  Compare simulation results with theoretical predictions for both random and oriented needle cases.

## Requirements

- Python 3.8+
- numpy
- matplotlib
- seaborn

Install dependencies with:

```sh
pip install -r requirements.txt
```

## Usage

Open [montecarlo_simulation.ipynb](montecarlo_simulation.ipynb) in Jupyter Notebook or VS Code and run the cells sequentially.

### Main Sections

- **Buffon's Needle Simulation:**  
  Run the simulation and estimate π.

- **Confidence Interval Calculation:**  
  Assess the reliability of the π estimation.

- **Oriented Needles:**  
  Explore how fixing the needle orientation changes the crossing probability and allows estimation of other irrational numbers (e.g., √2, √3).

- **Visualization:**  
  Visualize the distribution of estimated values and the effect of orientation.

- **Mathematical explanation:**  
  Provide a detailed theoretical explanation for the revisited needles experiment.

## Project Structure

- `montecarlo_simulation.ipynb` — Main notebook containing code, explanations, and results.

## References

- [Buffon's Needle - Wikipedia](https://en.wikipedia.org/wiki/Buffon%27s_needle)
- https://pub.math.leidenuniv.nl/~finkelnbergh/seminarium/stelling_van_Buffon.pdf
- Monte Carlo methods in probability and statistics

---

**Author:**  
Antonio Schirò

**License:**  
MIT License