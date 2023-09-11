# Rust File Compression with flate2 📦

Welcome to the documentation for the Rust File Compression program using the `flate2` crate! This guide introduces you to a Rust application that compresses files using the Gzip compression algorithm. Whether you're a developer or just getting started with Rust, you'll find this program useful. Let's explore its features and usage! 🚀

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [File Compression](#file-compression)
- [How it Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Rust File Compression program showcases how to compress files using Gzip compression, a popular method for reducing file sizes. It takes two command-line arguments: the source file to compress and the target file where the compressed content will be saved.

## Usage

To use the Rust File Compression program, follow these steps:

1. Ensure you have Rust and Cargo installed on your system.

2. Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/your-username/file-compression.git
   cd file-compression
   ```

3. Build the program:

   ```bash
   cargo build
   ```

4. Compress a file:

   ```bash
   cargo run source.txt target.gz
   ```

   Replace `source.txt` with the name of the file you want to compress and `target.gz` with the name you want for the compressed file.

5. The program will compress the file and display information about the original and compressed file sizes, as well as the elapsed time for compression.

## File Compression

This program uses the Gzip compression algorithm provided by the `flate2` crate. Gzip compression is widely used for file compression because it offers good compression ratios while maintaining reasonable compression and decompression speeds.

## How it Works

This program performs the following steps:

1. It checks if the correct number of command-line arguments is provided (source and target file names).

2. It reads the source file and opens an output stream for the target file.

3. It creates a Gzip encoder and copies the source file's content to it, compressing as it goes.

4. It finishes the compression and saves the compressed content to the target file.

5. It prints information about the original and compressed file sizes, as well as the time taken for compression.

## Contributing

Contributions are welcome! If you have ideas for improvements or find any issues, please feel free to open a pull request. Let's collaborate to enhance this Rust File Compression program.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the program according to the terms of the license.

---

Explore the Rust File Compression program, reduce your file sizes efficiently, and save storage space with ease. Happy file compression! 📦🚀
