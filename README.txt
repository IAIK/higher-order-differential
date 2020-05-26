# Compilation
Compile with:
g++ -std=c++0x -g -O2 -funroll-loops -march=native -mtune=native zero_sum_tester.cpp -o zero_sum_tester -lcrypto -lm

# Usage
<program> <n> <t> <num_rounds> <num_bits_active>
n = block size
t = number of cells
num_rounds = number of rounds

# Other settings
Other settings can be changed at the top of the file and at the beginning of the main() function. These settings include:
- Changing the degree of the round function
- Changing the cipher
- Setting whether the round constants and keys are randomly chosen or not
- Changing the affine layer matrix where appropriate
- and much more
