# Web Server on Rust v3

A simple and efficient web server built using Rust. This project demonstrates basic web server functionality, including handling HTTP requests, serving static files, and managing multiple connections asynchronously.

## Features

- **Asynchronous handling of requests:** Uses `tokio` to handle multiple connections concurrently.
- **Serving static files:** Capable of serving HTML, CSS, JavaScript, and other static assets.
- **HTTP request parsing:** Parses basic HTTP requests to serve the appropriate content.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Rust](https://www.rust-lang.org/tools/install) (version 1.56.0 or newer)
- [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Junsious/web-server-on-rust-v3.git
   ```

2. Navigate to the project directory:

   ```bash
   cd web-server-on-rust-v3
   ```

3. Build the project:

   ```bash
   cargo build --release
   ```

4. Run the server:

   ```bash
   cargo run
   ```

## Usage

Once the server is running, you can access it by navigating to `http://localhost:8080` in your web browser. Static files can be served by placing them in the `static/` directory.

## Project Structure

- **src/main.rs:** The main entry point of the application, where the server is started.
- **static/:** Directory where static files (HTML, CSS, JS, etc.) are served.
- **Cargo.toml:** The configuration file that includes project dependencies like `tokio`.

## Example

If you place an `index.html` file in the `static/` folder, it will be served when you visit `http://localhost:8080/index.html`.

## Built With

- [Rust](https://www.rust-lang.org/) - A fast, memory-safe programming language.
- [Tokio](https://tokio.rs/) - An asynchronous runtime for the Rust programming language.

## Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
