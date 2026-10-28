# Number Sequence

A small Java console exercise that reads an integer and prints the numbers from 1 up to that integer using a `for` loop.

## Current behavior

Despite the repository name, the program currently prints a sequence; it does not calculate the sum. For input `5`, it prints `1 2 3 4 5`. For a value below 1, the loop prints no numbers.

## Source

- [NumberSequence.java](gitHub/src/gitHub/NumberSequence.java): console input with `Scanner` and an ascending loop. Simple German comments explain the steps.
- Package: `gitHub`.
- Requirements: a Java JDK with `javac`; no external dependencies.

## Compile and run

Run these commands from the repository root:

```bash
javac -encoding UTF-8 -d out gitHub/src/gitHub/NumberSequence.java
java -cp out gitHub.NumberSequence
```

You can also import the existing Eclipse project from the `gitHub` folder and run `NumberSequence.main()`.

Numeric input is expected; input validation is not implemented. The naming and comments update preserves the existing loop and output.
