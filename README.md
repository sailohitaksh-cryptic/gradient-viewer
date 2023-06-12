# gradient-viewer

# Gradient Visualization

This script allows you to visualize gradients based on color values provided in a JSON file. Each gradient is represented by a set of color stops defined by their positions and corresponding hex codes.

## Prerequisites

- Python 3.x
- Matplotlib library

## Usage

1. Make sure you have Python installed on your system.
2. Install the required dependencies by running the following command:
`pip install matplotlib`
3. Update the JSON data file with the desired gradients. Each gradient should include an index (`idx`), a set of color stops (`color`), and optional text colors (`text`, `textBg`).
4. Save the updated JSON data file.
5. Execute the script by running the following command: `python gradient_visualization.py`
6. 6. The script will generate individual plots for each gradient, displaying the color transition and a colorbar indicating the position values.

## Customization

- Modify the JSON data file (`gradients.json`) to add or update gradients.
- Adjust the code to customize the plot settings, such as title, axis labels, or figure size.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to use and modify this code as per your requirements.
