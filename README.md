 # Custom System Calls for xv6 Project

## Overview
This project aims to enhance the functionality of the xv6 operating system by implementing custom system calls. By introducing these custom system calls, we can expand the capabilities of xv6 and facilitate new ways for user programs to interact with the operating system kernel.

## Features
1. **Custom System Calls**: Addition of new system calls to provide unique functionality not present in the original xv6 implementation.
2. **Enhanced User Program Interaction**: Users can now access advanced features through the custom system calls.
3. **Improved Kernel Functionality**: The custom system calls enhance the kernel's capabilities, enabling greater flexibility and control.

## Installation
Follow these steps to install and run the xv6 operating system with the custom system calls:
1. Clone the xv6 repository from [GitHub](https://github.com/mit-pdos/xv6-public).
2. Navigate to the xv6 directory.
3. Apply the custom system calls patch provided in this project.
4. Recompile and run xv6 as per the original setup instructions.

## Custom System Calls
The following custom system calls have been implemented as part of this project:
- **CustomCall1**: set_proc_name (This function sets the “name” field in the PCB (process control block) of the process specified).
- **CustomCall2**: print_proc_ancestors (This function requests the OS to print the ancestor processes of the process specified).

## Usage
To utilize the custom system calls in a user program, follow these guidelines:
1. Include the necessary headers defining the custom system call numbers.
2. Implement the functionality utilizing the custom system calls in your user program.
3. Compile the program with the updated xv6 kernel supporting custom system calls.
4. Run the program to test the new functionalities.

## Contribution
Contributions to this project are welcome! Feel free to fork the repository, make improvements, and submit a pull request. Your contributions will help enhance the xv6 operating system for the community.

## Support
If you encounter any issues or have questions regarding the custom system calls implementation, please [open an issue] on the project repository. We are here to assist and resolve any queries you may have.
