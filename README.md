# Custom Vector — Modern C++

A custom implementation of a dynamic array container inspired by `std::vector`, developed to practice Modern C++ programming, memory management, and resource ownership.

## Features

- Generic container implementation using C++ templates
- RAII-based dynamic memory management with a custom `ArrayPtr` class
- Copy and move constructors and assignment operators
- Dynamic capacity management with `Reserve` and `Resize`
- Element insertion and removal using `PushBack`, `PopBack`, `Insert`, and `Erase`
- Iterator support and container comparison operators
- Assertion-based tests in `main.cpp`

## Technologies

- C++17
- C++ Standard Library
- Templates and move semantics
- RAII and dynamic memory management

## Project Structure

- `simple_vector.h` — templated dynamic array implementation
- `array_ptr.h` — RAII wrapper for dynamically allocated arrays
- `main.cpp` — usage examples and tests

## Build and Run

Requires a C++17-compatible compiler.

```bash
g++ -std=c++17 -Wall -Wextra -pedantic main.cpp -o custom_vector
./custom_vector
```

On Windows, run `custom_vector.exe` after compilation.

## Notes

This project is an educational implementation intended to explore container internals and Modern C++ techniques. It is not a complete replacement for `std::vector`.
