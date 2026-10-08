# Rustscan-Scanning-Tool
RustScan is an ultra-fast, modern port scanner written in Rust that can scan all 65,000 ports in just a few seconds and automatically pipe open ports directly into Nmap.

## Installation steps.

1. Run the below command in the terminal to download package manger and tool.

   ```
   sudo apt update
   sudo apt install cargo rustc
   ```
2. Install RustScan via Cargo with below command.
    ```
    cargo install rustscan
   ```
3.  Add Cargo Binaries to your PATH.
     ```
     echo 'export PATH="$HOME/.cargo/bin:$PATH"' >> ~/.zshrc
     ```
4. source the `zshrc` file run the rust command.
    ```
    source ~/.zshrc
    ```
5. Run the rustcommand to with the help menu to check the options.
    ```
    rustscan --help
    ```
