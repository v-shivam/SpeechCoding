# EE623 Final Assignment 2

This repository contains the final assignment for the EE623 course. The assignment involves signal processing tasks using Python.

## Repository Structure

```
.DS_Store
ee623-final-assignment-2___final.ipynb
Outputs/
    .DS_Store
Sample_speech/
    .DS_Store
```

- 

ee623-final-assignment-2___final.ipynb

: The main Jupyter notebook containing the code for the assignment.
- 

Outputs

: Directory for storing output files.
- 

Sample_speech

: Directory for storing sample speech files.

## Requirements

The following Python packages are required to run the notebook:

- `numpy`
- `scipy`
- `librosa`
- `soundfile`

You can install the required packages using pip:

```sh
pip install numpy scipy librosa soundfile
```

## Usage

1. Clone the repository:

```sh
git clone <repository-url>
cd <repository-directory>
```

2. Open the Jupyter notebook:

```sh
jupyter notebook ee623-final-assignment-2___final.ipynb
```

3. Run the cells in the notebook to execute the code.

## Functions

### `segsnr`

Calculates the segmental signal-to-noise ratio (SNR) between a reference signal and a synthesized signal.

**Parameters:**
- `reference_signal`: The reference signal.
- `synthesized_signal`: The synthesized signal.
- `fs`: Sampling frequency.
- `frame_size`: Frame size in seconds (default is 0.03).
- `overlap`: Overlap between frames (default is 0.75).

**Returns:**
- Segmental SNR value.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

This assignment was completed as part of the EE623 course. Special thanks to the course instructors (Rohit Sinha Sir).

---

Feel free to modify this README to better suit your needs.
