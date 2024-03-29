Here is a quickstart guide for getting started with Rust:

## Installing Rust

The easiest way to install Rust is through rustup, the Rust installer and version management tool. Follow these steps:

1. Open your terminal/command prompt.

2. For Unix systems (Linux, macOS), run:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

3. For Windows, visit https://www.rust-lang.org/tools/install and download the installer. Run the .exe file and follow the instructions.

4. Once installed, you can update to the latest Rust version by running:

```bash
rustup update
```

## Creating a New Project

Rust comes bundled with Cargo, the official build tool and package manager. To create a new project:

1. Open your terminal and navigate to the directory where you want your project.

2. Run the following command to create a new binary project called "hello-rust":

```bash
cargo new hello-rust --bin
```

This will generate a new directory with a Cargo.toml file for dependencies and a src/main.rs file for your Rust code.

## Writing Some Code

Open the src/main.rs file in your favorite code editor and replace the contents with:

```rust
fn main() {
    println!("Hello, world!");
}
```

## Running the Project

To run your new Rust program:

1. In your terminal, navigate to the hello-rust directory.

2. Run the following command:

```bash
cargo run
```

You should see "Hello, world!" printed to the console. [1][2][6]

This covers the basics of installing Rust, creating a new project, writing some code, and running it. The Rust book[1] has many more examples to continue learning Rust.

Citations:
[1] https://doc.rust-lang.org/book/ch01-00-getting-started.html
[2] https://www.youtube.com/watch?v=4q3Z5RBX7hQ&t=0
[3] https://www.rustafied.com/getting-started-in-rust-experimental
[4] https://web.mit.edu/rust-lang_v1.25/arch/amd64_ubuntu1404/share/doc/rust/html/book/first-edition/getting-started.html
[5] https://stackoverflow.blog/2021/03/15/getting-started-with-rust/
[6] https://www.rust-lang.org/learn/get-started
[7] https://www.programiz.com/rust/getting-started
[8] https://www.youtube.com/watch?v=hH_jQFFO4Jw
