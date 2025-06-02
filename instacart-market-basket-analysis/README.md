# Instacart Market Basket Analysis

This project analyzes the Instacart market basket data to uncover insights into customer purchasing behavior. The analysis includes data loading, cleaning, exploration, and visualization steps to understand how customers interact with products on the Instacart platform.

## Project Structure

The project consists of the following files:

- **notebooks/instacart_market_basket_analysis.ipynb**: This Jupyter Notebook contains the analysis of the Instacart market basket data. It includes data loading, cleaning, exploration, and visualization steps.

- **data/**: This directory contains the datasets used in the analysis:
  - **instacart_orders.csv**: Contains order data from Instacart, detailing each order placed by customers.
  - **products.csv**: Contains information about the products available on Instacart, including product IDs and names.
  - **departments.csv**: Contains department information for the products, categorizing them into different sections.
  - **aisles.csv**: Contains aisle information for the products, providing a more granular categorization.
  - **order_products.csv**: Contains the relationship between orders and products, detailing which products were included in each order.

- **requirements.txt**: Lists the Python packages required to run the Jupyter Notebook and perform the analysis.

## Setup Instructions

To set up the environment for this project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```
5. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Analysis

To run the analysis, open the Jupyter Notebook located in the `notebooks` directory:

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```
2. Open `instacart_market_basket_analysis.ipynb` and execute the cells to perform the analysis.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.