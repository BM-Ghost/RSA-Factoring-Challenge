### Task 0: Factorize all the things!

This task involves factoring as many numbers as possible into a product of two smaller numbers.

**Usage:**
```bash
factors <file>
```
Where `<file>` is a file containing natural numbers to factor, with one number per line. Each line represents a valid natural number greater than 1, and the file will always end with a new line.

**Output format:**  
The output displays factorizations in the format `n=p*q`, where `p` and `q` are the two smaller numbers constituting the product.

Your program should:
- Work on the numbers of the file in any order
- Run without any dependency as you won’t be able to install anything on the machine where the program will run
- Finish within 5 seconds or it will be terminated
- Push all scripts, source code, etc., to your repository
- The executable to run will be named `factors`

### Task 1: RSA Factoring Challenge

This task is similar to Task 0, but with specific constraints:
- The numbers `p` and `q` are always prime numbers
- Each file contains only one number to factor

The goal is to factorize RSA numbers and find the two prime numbers given only `n`.

**Usage:**
```bash
rsa <file>
```
Where `<file>` contains a single number to factorize, and the output displays the factorization in the format `n=p*q`, where `p` and `q` are prime numbers.

Example usage and expected output are provided in the README file in the repository.

GitHub repository: [RSA-Factoring-Challenge](https://github.com/BM-Ghost/RSA-Factoring-Challenge)  
Files: `factors`, `rsa`