# rustcraft

A Rust-based command-line tool for querying Minecraft server status.

## Features

- Supports modern and legacy Minecraft protocols (including SRV)
- Retrieves server info: version, player count, MOTD
- Fetches Forge and mod details

## Quick Start

1. [Install Rust](https://www.rust-lang.org/tools/install)

2. Clone the repository:
   ```
   git clone https://github.com/5vx/rustcraft.git
   cd rustcraft
   ```

3. Build the project:
   ```
   cargo build --release
   ```

4. Run rustcraft:
   ```
   ./target/release/rustcraft <hostname> <port>
   ```

   Example:
   ```
   ./target/release/rustcraft mc.example.com 25565
   ```
