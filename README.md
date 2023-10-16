## Summary

The algo basilcally helps in finding compounded words inside a dictionary of words and return the longest compounded word and the second longest under < 1s [tested over 100,000+ words]

## Approach and design decision

Step by step following the code flow

- `File Read` - Reading of the file using fetch and storing into array [sorted]
- `Set` - 2 storing container one is array another is Set
- `Sorting` - Sorting of the elements in decending order by word length
- `Recursive DFS` - Use of Backtracking and spliting the word every time into prefix and postfix
- `Skipping Second longest Compounded Word` - Before executing the function the longestWord is deleted from wordSet to prevent searching the same word.
