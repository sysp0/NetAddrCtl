# NetAddrCtl

NetAddrCtl is a command-line utility for Linux (Debian/Ubuntu) written in C. It allows users to assign and remove IP addresses from network interfaces using `ioctl` system calls.

## Key Features

- 🖥️ **IP Address Assignment**: Assign IP addresses to network interfaces.
- 🗑️ **IP Address Removal**: Remove IP addresses from network interfaces.
- 🖱️ **Command-Line Interface (CLI)**: Easy-to-use CLI commands.
- 🐧 **Linux Distribution Support**: Designed for Debian/Ubuntu.
- ⚙️ **Error Handling**: Robust error management.

## ToDo List

### 2. IP Management Features
- **Add IP Address** 
  - [ ] Write a function to add an IP address to a network interface using `ioctl`.
  - [ ] Test the function to ensure it works with different network interfaces.

- **Remove IP Address**
  - [ ] Write a function to remove an IP address from a network interface using `ioctl`.
  - [ ] Test the function for various scenarios to ensure it handles errors properly.

### 3. Command-Line Interface (CLI)
- **Design and Implement CLI**
  - [ ] Create commands for adding and removing IP addresses (e.g., `--add`, `--remove`).
  - [ ] Add help messages to guide users on how to use the CLI.

- **Test CLI**
  - [ ] Write simple tests to check if the CLI commands work correctly.

### 4. Error Handling
- **Implement Error Handling**
  - [ ] Identify potential errors when adding or removing IP addresses (e.g., interface errors).
  - [ ] Add detailed error messages to help with troubleshooting.

### 5. Documentation
- **User Documentation**
  - [ ] Write a brief guide in `README.md` on how to use the tool.
  - [ ] Include examples of commands and expected outputs.

- **Developer Documentation**
  - [ ] Explain the code structure and main functions either in the code comments or a separate file.

### 6. Testing and Validation
- **Manual Testing**
  - [ ] Perform manual tests to ensure adding and removing IP addresses works on different network interfaces.
