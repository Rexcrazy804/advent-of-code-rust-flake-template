# Template for solving Advent of Code puzzles in Rust with Nix Flakes

## Usage with Nix

1. run ```nix develop```
2. open your favourite text editor / ide and have fun
3. (optional) use [nix-direnv](https://github.com/nix-community/nix-direnv) to automatically load the environment when switching to repo's directory

> you may directly write this template onto the **current** working directory using\
```nix flake init -t github:Rexcrazy804/advent-of-code-rust-flake-template```

## Usage (preserved from fork parent)

1. Create a new project from the template repository:
   - Using GitHub’s templating feature: Simply click the Use this template [button](https://github.com/new?template_name=advent-of-code-rust-template&template_owner=bravit) on the repository page, create a new repository, and then open it in [RustRover](https://www.jetbrains.com/rust/) by selecting *File | New | Project From Version Control…*.
   -  Adding the template to RustRover: You can integrate the template directly into RustRover and use the regular New Project wizard.

2. Whenever you're ready to start solving a new day's puzzle:
   - Open the `bin` folder, copy and paste the `NN.rs` file into it, and give it the corresponding name (`01.rs`, `02.rs`, etc.).
   - In the `input` folder, create and fill the input data file (`01.txt`, `02.txt`, etc.).
   - Fill in the `DAY` constant in the freshly created file.
   - Run the current day's solution to check if it compiles (you can use the gutter icon next to the `main` function).
   - Fill in `<TEST-INPUT>`.
   - Write the expected answer for the test data in the `assert_eq` statement in *Part 1*.
   - Now you're ready to write your solution in the `part1` function (inside `main`).
   - Use `Shift+F10` (Win/Linux) or `Ctrl-R` (macOS) to re-run the same program.

3. When you're done with the first part of the puzzle, use folding to hide *Part 1*.

4. Uncomment *Part 2*, fill in the test data assertion, and start solving it.
