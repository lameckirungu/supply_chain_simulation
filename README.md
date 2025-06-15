# Supply Chain Simulation

This project simulates a simple supply chain consisting of a Supplier, a Warehouse, and a Retailer. The simulation tracks inventory levels, sales, demand, and stockouts over a specified number of days.

## Features

- Simulates production at the Supplier, inventory management at the Warehouse, and sales at the Retailer.
- Includes reordering logic based on reorder points and order quantities.
- Records inventory levels and sales data over time.
- Provides visualizations of inventory levels, demand vs. sales, and stockouts.
- Calculates key performance metrics like total demand, sales, stockouts, and inventory fill rate.

## Getting Started

### Prerequisites

- Python
- SimPy library (`pip install simpy`)
- NumPy library (`pip install numpy`)
- Pandas library (`pip install pandas`)
- Matplotlib library (`pip install matplotlib`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/lameckirungu/supply_chain_simulation.git

2. Navigate to the directory:
    ```
    cd supply_chain_simulation
    ```
3. Install the required libraries:

   ```bash
   pip install simpy numpy pandas matplotlib
   ```

### Running the Simulation

1. You can run the simulation directly from a Python environment or a Jupyter Notebook (like Google Colab).
2. Execute the Python script or run the cells in the notebook.

The simulation will run for the specified number of days (default is 30 days) and display the visualizations and performance metrics at the end.

## Code Structure

- **`SupplyChainEntity`**: Base class for all entities in the supply chain.
- **`Supplier`**: Represents the entity that produces items.
- **`Warehouse`**: Represents the entity that stores and distributes inventory.
- **`Retailer`**: Represents the entity that sells to customers.
- **`SupplyChainSimulation`**: The main class that sets up and runs the simulation.

## Customization

You can modify the simulation parameters within the `SupplyChainSimulation` class, such as:

- `simulation_days`: The number of days to simulate.
- Initial inventory levels, production rates, lead times, reorder points, and order quantities for each entity.

## Contributing

Contributions are welcome! If you find a bug or want to add a new feature, feel free to open an issue or submit a pull request.

## License

This project is licensed under the  MIT License - see the LICENSE file. 