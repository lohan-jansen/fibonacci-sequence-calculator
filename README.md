# Fibonacci Sequence Calculator

A program that calculates the index of the first term in the Fibonacci sequence to contain N digits. The programm uses a fibonacci function to calculate the posistion of the term with N digits. The function defines the first two terms in ana array and sets the index of the array. The function then uses simple summation of the last and second to last terms in the array to calculate the next term and appends the calculated value into the array. The length of the calculated digit is then compared to N. if the the lenth of the calcualted value is smaller than N, the index is increased by 1 and calculation is repeated with the last two values in the array. Once the length of digits of the calculated value equates to N the index of the value in the array is reported.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

git clone https://github.com/lohan-jansen/fibonacci-sequence-calculator.git


2. Install the required dependencies using pip:

pip install -r requirements.txt


## Usage

### Running as a standalone program

To run the program as a standalone Python program, use the following command:

python fibonacci.py <N>

Replace `<N>` with the number of digits you want to find in the Fibonacci sequence.

The program will output the index of the first term in the Fibonacci sequence to contain N digits.

### Running as a Docker container

To run the program as a Docker container, use the following commands:

1. Build the Docker image:

docker build -t fibonacci-term .

2. Run the Docker container:

docker run --rm fibonacci-term <N>

### Examples

Example usage:

python fibonacci.py 2

Output: 7

Explanation: The first term in the Fibonacci sequence to contain 2 digits is the 7th term (13).

Example usage:

docker run --rm fibonacci-term 3

Output: 12

Explanation: The first term in the Fibonacci sequence to contain 3 digits is the 12th term (144).

Example usage:

docker run --rm fibonacci-term 10

Output: 45

Explanation: The first term in the Fibonacci sequence to contain 10 digits is the 45th term (1134903170)

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes and commit them
4. Push your changes to your forked repository
5. Submit a pull request

This program was written by Lohan Jansen.

## License

This project is licensed under the MIT License. You can find the full text of the license in the LICENSE file.

## Contact

If you have any questions or comments about this project, please contact Lohan Jansen at lohanjansen007@gmail.com.
