# s21_math

**An educational project from School 21: a reimplementation of the standard C `<math.h>` library functions in pure C without using built-in math functions.**

**The project includes precise implementations of key mathematical functions such as trigonometric, logarithmic, power, rounding, and absolute value operations. All logic is written manually based on mathematical theory and Taylor expansions.**

**All modules are tested using the `check` unit testing framework, with code coverage tools integrated for quality control.**

```bash
make             # build the static math library and test binary

make test        # compile and run unit tests

make gcov_report # generate HTML coverage report

make main        # compile and run sample main.c using the library

make clean       # remove build artifacts and coverage data

make rebuild     # clean and fully rebuild the project
```