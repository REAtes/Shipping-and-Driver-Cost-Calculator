# Shipping and Driver Cost Calculator

This Python project includes functions for calculating shipping costs, driver costs, and money earned from trips using the Nile service.

## Project Structure

- **script.py**: This file contains the main functions for calculating shipping and driver costs, as well as money made from trips.
- **nile.py**: Contains functions to calculate distances between coordinates and defines shipping prices.
- **test.py**: Provides test functions to ensure the correctness of the main functions.

## How to Use

1. Clone this repository to your local machine.

2. Run the `script.py` file to test the provided functions.

## Functions

### `calculate_shipping_cost`

This function calculates the shipping cost based on the distance between two coordinates and the chosen shipping type.

- Input: `from_coords`, `to_coords`, `shipping_type`
- Output: Formatted shipping cost as a string (e.g., "$1.04")

### `calculate_driver_cost`

This function calculates the cost for the least expensive driver to cover a given distance.

- Input: `distance`, `*drivers` (variable number of Driver objects)
- Output: Tuple containing the final price and the least expensive driver (e.g., `(200, <Driver object>)`)

### `calculate_money_made`

This function calculates the total money earned from trips. It takes keyword arguments, where each keyword represents a trip.

- Input: Keyword arguments for trips (e.g., `UEXODI=trip1, DEFZXIE=trip2`)
- Output: Total money earned as a number (e.g., `445`)

## Testing

The project includes a testing framework in `test.py` that checks the correctness of the main functions.

To run the tests, simply execute the `script.py` file, which includes calls to the test functions.
