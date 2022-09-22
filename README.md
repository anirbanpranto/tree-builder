# Tree Builder
While solving leetcode problems I noticed that the binary tree problems are hard to test on my system because the Leetcode given input is an array and I had to build a tree and populate it by using method calls every time I solved one of those problems. So this is a simple utility function to help me build a tree really fast from an array input and test my problems. I suggest that you build your own, because to be fair I write pretty bad code usually. (I am much more comfortable with Typescript and C++ than I am with python.)

I hastily built it in like 10 mins, so pardon bros.

## How to use

```
1. Copy the code to your file
2. Call the `BuildTree` class by passing an array of values in the constructor.
3. The returned object has a .root member variable, you can use that to test your leetcode functions Ez
4. _print_tree() method is a simple DFS to print out the tree itself to check if the values are correct.
```

## Array format
```
[1,2,3,None,4,None,5]
```
Here 1 is root. 1 has two children, 2 and 3. 2 has two children None and 4, 3 has two children None and 5.
So basically you write the array in a DFS manner. It starts from the root, then the children of root. Then children of first child and then children of second child and so on.

## Screenshots
![code](https://github.com/anirbanpranto/tree-builder/resource/code.png)
![output](https://github.com/anirbanpranto/tree-builder/resource/output.png)

## Contribution
Feel free to contribute to make the code better and more usable.

