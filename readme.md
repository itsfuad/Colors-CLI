# Colors CLI

Colors CLI is a simple Go package that provides functionality to print colored text to the terminal using ANSI escape codes.

## Installation

To install the package, run:

```sh
go get github.com/itsfuad/colors-cli
```

## Usage

Here is an example of how to use the Colors CLI package:

```go
package main

import (
    "github.com/itsfuad/colors-cli"
)

func main() {
    colors.RED.Println("This is a red text")
    colors.GREEN.Printf("This is a %s text\n", "green")
    colors.BLUE.Print("This is a blue text")
}
```

## Available Colors

- `RESET`
- `RED`
- `BOLD_RED`
- `GREEN`
- `YELLOW`
- `BOLD_YELLOW`
- `ORANGE`
- `BROWN`
- `BRIGHT_BROWN`
- `BLUE`
- `BOLD_BLUE`
- `PURPLE`
- `CYAN`
- `WHITE`
- `GREY`
- `BOLD`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Author

Fuad Hasan