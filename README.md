<h2># Rust Web Scraper</h2>

<p>This Rust project demonstrates how to scrape and print all hyperlinks (`<a>` tags) from a webpage using the `reqwest` and `select` crates. Error handling is managed using the `error-chain` crate.</a>

<p>## Features</p>

<li> Fetches a webpage using `reqwest`.</li>
<li> Parses the HTML content using the `select` crate.</li>
<li> Prints all hyperlinks found in the webpage.</li>
<br>
<p>## Dependencies</p>

<p>This project uses the following dependencies:</p>

<li> [`reqwest`](https://crates.io/crates/reqwest): For making HTTP requests.</li>
<li> [`select`](https://crates.io/crates/select): For parsing HTML documents.</li>
<li> [`error-chain`](https://crates.io/crates/error-chain): For error handling.</li>

## Installation

1. Ensure you have [Rust](https://www.rust-lang.org/tools/install) installed.
2. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/rust-web-scraper.git
    ```
3. Navigate to the project directory:
    ```sh
    cd rust-web-scraper
    ```
4. Build the project:
    ```sh
    cargo build
    ```

## Usage

Run the project with the following command:

```sh
cargo run
