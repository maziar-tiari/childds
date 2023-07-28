# Child Directory Command Executor (childds)

This bash script allows you to execute a command in all child directories of the current directory. This can be particularly useful when you're working on a project with multiple sub-projects, each in its own directory.

## Usage

To use this script, simply pass the command you want to execute as an argument. For example, if you want to run `git pull` in all child directories, you would run:
<br/>`childds git pull`

## Installation

First, clone this repository to your local machine using `git`:

`git clone https://github.com/maziar-tiari/childds.git`

Then, navigate to the directory containing the script and make it executable:
`chmod +x childds`

Finally, to make the script globally available, move it to a directory that's on your system's PATH. The `/usr/local/bin` directory is a common choice for this on Unix-like systems:
`sudo mv childds /usr/local/bin/childds`

_Note: Depending on your system, you may need to restart your terminal or source your shell profile to be able to use the `childds` command._

Now, you can run the script as described in the Usage section.

## Contributing

Contributions are welcome! If you have a bug to report, a feature to request, or a change you'd like to make to the code, please open an issue or a pull request.

## License

This project is licensed under the GPL License. See the `LICENSE` file for more details.
