# Image Editing Script

This script uses the Python Imaging Library (PIL) to edit images in a specified folder. It applies a sharpen filter and enhances the contrast of each image, saving the edited versions in a separate folder.

## Requirements

- Python 3.x
- PIL (Python Imaging Library)

## Installation

1. Make sure you have Python 3.x installed on your system. You can download the latest version of Python from the official website: [python.org](https://www.python.org).

2. Install the required PIL library by running the following command:

   ```
   python3 -m pip install --upgrade pip
   python3 -m pip install --upgrade Pillow
   ```

## Usage

1. Place the images you want to edit in a folder and note down its path.

2. Create a separate folder where you want the edited images to be saved. Note down its path as well.

3. Open a text editor and create a new Python file.

4. Copy the provided code into the Python file.

5. Replace the values of the `path` and `pathOut` variables with the paths you noted down in steps 1 and 2.

6. Save the Python file with a `.py` extension.

7. Open a terminal or command prompt and navigate to the directory where you saved the Python file.

8. Run the script by executing the following command:

   ```
   python3 your_script_name.py
   ```

   Make sure to replace `your_script_name.py` with the actual name of your Python file.

9. The script will process each image in the specified folder, apply the sharpen filter and contrast enhancement, and save the edited versions in the designated output folder.

10. After the script completes, you can find the edited images in the output folder you specified.

## Customization

- **Sharpen filter**: If you want to change the type of filter applied, you can modify the line `img.filter(ImageFilter.SHARPEN)`. PIL provides various filters that you can choose from. Refer to the PIL documentation for more information.

- **Contrast enhancement**: To adjust the contrast enhancement, you can modify the `factor` variable. Higher values increase the contrast, while lower values decrease it. Experiment with different values to achieve the desired result.

## License

This script is provided under the [MIT License](LICENSE). Feel free to modify and use it according to your needs.
