# Save more time

This project aims to save you time when working with `semistandard-js` by simplifying its usage with a Makefile. Instead of typing long commands, you can use a shorter and more convenient approach.

## Getting Started

To get started, follow these simple steps:

Clone the repository

```bash
git clone https://github.com/samuelogboye/bash-scripts.git
```

Navigate to the semistandard-js directory:

```bash
cd bash-scripts/semistandard-js
```

Run the `make` command
```bash
make
```

This will make the `js` file executable and move it to the `/bin` directory, allowing you to use it conveniently.


## Using the "js" Command

Now that everything is set up, you can save time and keystrokes when using semistandard-js:

Instead of typing `chmod +x file` and `semistandard`, simply type:

```bash
js
```
This will make all JavaScript files in the current directory executable and run `semistandard` on them

*This saves you 21 characters of typing.*

### You can run `js` on a specific file

```bash
js file1
```

### You can run `js` on multiple files

```bash
js file1 file2 file3
```

Instead of typing `semistandard --fix` simply type

```bash
js f
```

*This saves 14 characters.*


The error output and behavior remain the same, so you only save more time when working with semistandard-js.


## Reporting Issues

If you encounter any bugs or issues, please report them or create an issue
