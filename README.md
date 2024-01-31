# Turtle-based Image Drawer

![Example Output](assets/output.png)

This Python script utilizes the Turtle graphics library to draw images in a creative way. It converts an input image into a simplified representation using binary thresholding, Canny Edge Detection, and Turtle graphics.

## Usage

### Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- AceD (Automated Canny Edge Detection) (`pip install ace-d`)
- Turtle Graphics Library (built-in with Python)

### How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/real0x0a1/DrawImageToTurtle.git
   ```

2. Navigate to the project directory:

   ```bash
   cd DrawImageToTurtle
   ```

3. Run the script with required arguments:

   ```bash
   python3 sketch.py --input input_image.jpg --output output_image --width 800 --height 600
   ```

   Adjust the `--input` to your input image path and `--output` to the desired output image name. You can also specify `--width` and `--height` for the dimensions of the turtle drawing area.

4. View the Output:

   The script will create an `.eps` file in the project directory. You can use online tools or command-line tools to convert the `.eps` file to a more common image format like PNG.

## Arguments

- `--input` (`-in`): Path to the input image file.
- `--output` (`-o`): Name of the output image file (without extension).
- `--width` (`-wt`): Width of the turtle drawing area.
- `--height` (`-ht`): Height of the turtle drawing area.

## Example

```bash
python3 sketch.py --input input_image.jpg --output output_image --width 800 --height 600
```

## Notes

- Tune the constants in the script (`THRESHOLD_VAL`, `SHAPE`, `CUTOFF_LEN`, etc.) according to your preference and the characteristics of the images you are working with.
- The script outputs an `.eps` file; you can convert it to a PNG or any other image format using available tools.

## Author

- Ali (Real0x0a1)

---
