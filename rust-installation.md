
# Installing Rust with `rustup`

Rust is a systems programming language focused on safety, speed, and concurrency. The recommended way to install Rust is via [`rustup`](https://rustup.rs/), a command-line tool for managing Rust versions and associated tools.

## 📦 Prerequisites

- A Unix-based system (Linux/macOS) or Windows
- Internet connection
- Basic command-line knowledge

## 🛠️ Installation Steps

### 1. Install `rustup`

#### On Unix (Linux/macOS):

Open your terminal and run:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

This will download and run the installation script. Follow the on-screen prompts to proceed.

### 2. Configure Your Path

After installation, ensure that Cargo’s `bin` directory is in your `PATH`.

- Unix (add to `~/.bashrc`, `~/.zshrc`, etc.):

```bash
export PATH="$HOME/.cargo/bin:$PATH"
```

- Windows: The installer usually updates your `PATH` automatically.

### 3. Verify Installation

Run the following command to confirm Rust is installed:

```bash
rustc --version
```

You should see output like:

```
rustc 1.XX.X (xxxxxxx YYYY-MM-DD)
```

## 🧰 What's Installed

- `rustc`: The Rust compiler
- `cargo`: Rust’s build system and package manager
- `rustup`: The version management tool
- Standard library and documentation

## 🔄 Updating Rust

To update Rust to the latest stable version, run:

```bash
rustup update
```

## ❌ Uninstalling Rust

If you ever need to uninstall Rust, simply run:

```bash
rustup self uninstall
```

## 📚 Additional Resources

- [Official Rust Book](https://doc.rust-lang.org/book/)
- [Crates.io - Rust package registry](https://crates.io/)
- [docs.rs - Documentation for Rust crates](https://docs.rs/)

---

Let me know if you want a section on installing nightly versions or setting up for specific editors.
