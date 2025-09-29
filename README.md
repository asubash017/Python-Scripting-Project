# Go Game Manager Utility 

A Python utility to manage and compile multiple Go-based game projects.  
This script scans a source directory for folders containing `_game` in their name, copies them into a target directory, compiles the `.go` code inside each folder, and generates a `metadata.json` file with game details.

---

## Features
- Automatically finds all game folders matching `_game`.
- Copies each game into a target directory (overwrites existing).
- Compiles `.go` source code inside each game folder using `go build`.
- Creates a `metadata.json` file containing:
  - List of game names
  - Number of games found

---

## Requirements
- **Python 3.8+**
- **Go (Golang)** installed and available in your system path (`go build` must work).

---

## Installation
1. Clone the repository or copy the script into your project folder.
2. Make sure **Go** is installed and accessible from your terminal:
   ```bash
   go version
    python get_game_data.py <source_directory> <target_directory>

