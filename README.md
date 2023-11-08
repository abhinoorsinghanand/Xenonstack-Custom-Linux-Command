# Xenonstack-Custom-Linux-Command
This is a task for a job opening in Xenonstack.

This README provides a concise overview of the `internsctl` command and its usage. You can further customize it to fit your specific needs.

# internsctl - Custom Linux Command

## Overview
`internsctl` is a custom Linux command for server operations. It simplifies tasks like retrieving system information, creating users, and managing files.

## Usage
```shell
./internsctl [command] [options]

Available Commands
cpu getinfo: Get CPU information.
memory getinfo: Get memory information.
user create <username>: Create a new user.
user list [--sudo-only]: List users (regular or with sudo permissions).
file getinfo [options] <file-name>: Get file information.
Examples
Display help: ./internsctl --help
Display version: ./internsctl --version
Retrieve CPU info: ./internsctl cpu getinfo
Create a user: ./internsctl user create <username>
List users: ./internsctl user list
Get file info: ./internsctl file getinfo <file-name>
Contributing
We welcome contributions. Please create issues or pull requests.
