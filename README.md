# CodeCooker: JSON Schema to C++ Code Generator

**CodeCooker** is a tool that generates C++ code based on JSON schema files. 
The generated C++ code will include classes and structures that match the types defined in the JSON schema.

## Features

- **Schema-Based Code Generation**: Automatically generates C++ classes and structures from JSON schema files.
- **Cross-platform Compatibility**: Designed to work on Linux, Windows, and macOS.

## Requirements

- **C++17** or later
- **Conan 2** package manager
- **CMake**

## Dependencies

CodeCooker relies on the following libraries:

- **nlohmann JSON** (`v3.9.1` or later)
- **Boost** (`v1.70` or later)

These dependencies are managed using **Conan 2**. Make sure Conan is installed on your system before proceeding.

### Installing Conan 2

If Conan 2 is not installed, you can install it as follows:

```bash
pip install conan --upgrade
```

## License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the LICENSE file for more details.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request, or report issues through the Issue Tracker.

1. Fork the repository.
2. Create a new feature branch (git checkout -b feature/my-new-feature).
3. Commit your changes (git commit -am 'Add some feature').
4. Push to the branch (git push origin feature/my-new-feature).
5. Open a Pull Request.

## Acknowledgments
- **nlohmann JSON**: For providing an excellent, modern JSON library for C++.
- **Boost**: For the extensive collection of high-quality C++ libraries.
