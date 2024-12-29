# Factor
Command-line tool to factor one or more numbers. Includes reduction, GCF/GCD and LCM operations.

About     | Current Release
----------|-----------------------
Version   | 0.1
Date      | December 28, 2024
Platforms | Windows, macOS, Linux
License   | [MIT License](LICENSE)

# Installation
1. Install [morlock.sh](https://morlock.sh)
2. `morlock install brombres/factor`

# Usage

    USAGE
      factor [OPTIONS] <integer> [<integer> ...]

    OPTIONS
      --all, -a
        Perform all operations: --factor, --gcd, --lcm, --prime, and --reduce.

      --factor, -f
        Prints all possible factors of each integer. For example,
        'factor --factor 36' prints 'Factors of 36: [1,2,3,4,6,9,12,18,36]'. This is
        the default operation if no other operations are selected.

      --gcd, --gcf, -g
        Prints the Greatest Common Divisor (GCD) of two or more integers. Also known
        as the Greatest Common Factor (GCF). For example, 'factor --gcd 100 150'
        prints 'GCD: 50'.

      --help, -h, -?
        Show this help text.

      --lcm, -l
        Prints the Least Common Multiple (LCM) of the prime factorizations of two or
        more integers. For example, 'factor --lcm 100 150' prints 'LCM: 300'.

      --prime, -p
        Prints the prime factors of each integer that can be multiplied together to
        produce the integer. For example, 'factor --prime 36' prints
        'Prime Factors of 36: [2,2,3,3]'.

      --reduce, -r
        Reduces or simplifies integers by dividing out all common factors above 1.
        For example, 'factor --reduce 640 480' prints 'Reduced: 4 3'.
