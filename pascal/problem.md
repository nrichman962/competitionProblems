Pascal's triangle is a mathematical construct where each row of the triangle is the sum of the sum of the two numbers above it:

```
      1
    1   1
  1   2   1
1   3   3   1
```

Your goal is to write a program to print a left-justified Pascal triangle of a given size with a variable keystone (top row). The triangle above is height 4, keystone 1, but not left justified. A triangle with a height of 5 and a keystone 2 would be:

```
2
2 2
2 4 2
2 6 6 2
2 8 12 8 2
```

## Input

The first input will be the number of triangle to generate. Each line following that will contain two numbers separated by a space. The first number will be the height of the triangle and the second will be the value of the keystone.

All of the input values will be 0 or higher.

## Output

The output must be a Pascal triangle with the size and keystone specified for each input. Each line of the triangle will consist of the numbers in that row separated by spaces.
