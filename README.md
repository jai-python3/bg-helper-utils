# bg-helper-utils
Collection of Python convenience scripts for BG tasks.


- [bg-helper-utils](#bg-helper-utils)
  - [Improvements](#improvements)
  - [Installation](#installation)
  - [Generate shell wrapper scripts](#generate-shell-wrapper-scripts)
  - [Exported scripts](#exported-scripts)
  - [Contributing](#contributing)
  - [To-Do/Coming Next](#to-docoming-next)
  - [CHANGELOG](#changelog)
  - [License](#license)


## Improvements

Please see the [TODO](TODO.md) for a list of upcoming improvements.

## Installation

Please see the [INSTALL](INSTALL.md) guide for instructions.

## Generate shell wrapper scripts

After executing `pip install bg-helper-utils`, execute this exported script: `make_executables_and_aliases.py`.<br>
This will create the wrapper shell scripts and a file containing aliases named `bg-helper-utils-aliases.txt` in the current directory.<br><br>
You can then add this line to your `.bashrc` or `.zshrc`:<br>
`source dir/bg-helper-utils-aliases.txt`<br>
where dir is the directory that contains the aliases file.


## Exported scripts

The following exported scripts are available:
- find-samplesheet
- find-batch-analysis-dir


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## To-Do/Coming Next

Please view the listing of planned improvements [here](TODO.md).

## CHANGELOG

Please view the CHANGELOG [here](CHANGELOG.md).

## License

[GNU AFFERO GENERAL PUBLIC LICENSE](LICENSE)
