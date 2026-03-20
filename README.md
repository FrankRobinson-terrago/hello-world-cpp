# Hello World - C++

A simple Hello World application written in C++. This project demonstrates a minimal C++ program that prints a greeting to the console.

## Prerequisites

- **Windows:** Visual Studio 2022 with MSVC compiler, or MinGW (g++)
- **Linux/macOS:** g++ or clang++

## Build & Run

### Windows (MSVC)
```bash
cl /EHsc /Fe:hello.exe main.cpp
hello.exe
```

### Windows (MinGW) / Linux / macOS
```bash
g++ -o hello main.cpp
./hello
```

## Expected Output

```
Hello, World!
```

## Project Structure

| File | Description |
|------|-------------|
| `main.cpp` | Entry point — prints "Hello, World!" to stdout |
| `README.md` | Project documentation |
| `.gitignore` | Git ignore rules for build artifacts |

## License

This project is open source and available for any use.

## Author

Frank Robinson — [frank.robinson@terragotech.com](mailto:frank.robinson@terragotech.com)
