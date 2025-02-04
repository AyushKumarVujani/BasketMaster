# BasketMaster


[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)  

## Overview

BasketMaster is a powerful tool designed to analyze customer purchasing patterns and segment customers for enhanced marketing strategies. By utilizing market basket analysis and clustering techniques, this project provides insights that help businesses optimize their sales approaches.

## Features

- **Market Basket Analysis**: Implements the Apriori Algorithm to discover frequent product combinations and generate actionable association rules.
- **Customer Segmentation**: Utilizes KMeans Clustering to categorize customers based on purchasing habits, enabling targeted marketing.
- **Interactive Visualizations**: Provides 3D visualizations for association rules and customer clusters, enhancing data interpretation.

## Technologies Used

- **Python**: Core programming language for data analysis and modeling.
- **Pandas & NumPy**: Libraries for data manipulation and numerical operations.
- **Scikit-learn**: Clustering algorithms and preprocessing techniques.
- **Plotly**: Interactive visualizations for insightful data exploration.
- **Faker**: Synthetic transaction data generation for analysis.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BasketMaster.git
   ```
2. Navigate into the project directory:
   ```bash
   cd BasketMaster
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Generate synthetic transaction data:
   ```bash
   python generate_data.py
   ```
2. Run market basket analysis:
   ```bash
   python market_basket_analysis.py
   ```
3. Perform customer segmentation:
   ```bash
   python customer_segmentation.py
   ```

## Data Generation

The project simulates customer transactions using the Faker library. A specified number of products, customers, and transactions are generated, allowing for realistic testing of algorithms and methodologies.

## Market Basket Analysis

Utilizes the Apriori Algorithm to identify strong associations between products in customer transactions. It evaluates combinations based on specified thresholds for support and confidence, yielding valuable insights into customer buying behaviors.

## Customer Segmentation

Employs KMeans Clustering to group customers based on their purchasing patterns, helping businesses identify high-value customer segments and enhance marketing effectiveness.

## Visualization

Interactive 3D visualizations generated using Plotly:

1. **Association Rule Visualization**: Displays the top association rules based on support, confidence, and lift.
2. **Customer Cluster Visualization**: Illustrates customer segments, aiding the understanding of purchasing behaviors.

## Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request. For major changes, please open an issue first to discuss your ideas.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please contact [ayushkmr527@gmail.com](mailto:ayushkmr527@gmail.com).

## Acknowledgements

Special thanks to the open-source community and all contributors!
