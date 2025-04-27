# lookuptable
Trigonometry Calculation using Look Table Method and Rust Language

# Kalkulator Trigonometri

A fast trigonometric calculator that uses lookup tables to quickly compute sine, cosine, and tangent values.

## Features

- Calculates sine, cosine, and tangent for any angle
- Uses pre-computed lookup tables for efficient calculation
- Visualizes sine wave with highlighted angle position
- Interactive display of lookup table values
- Clean and intuitive user interface

## Implementation Details

The application uses a lookup table approach with 360 pre-computed values (one for each degree) to avoid expensive floating-point calculations at runtime. The implementation includes:

- Lookup tables for sine and cosine values
- Angle input in degrees
- Real-time visualization of the sine wave
- Option to inspect the lookup table contents

## Requirements

- Rust 1.70 or higher
- egui/eframe crates for the GUI

## Building and Running

1. Clone the repository
2. Build and run with Cargo:

```
cargo build --release
cargo run --release
```

## Screenshots

(Add screenshots here)

## License

(Add license information here)
