# Add and Search Word - Data structure design

Design a data structure that supports the following two operations:
```
void addWord(word)
bool search(word)
```
search(word) can search a literal word or a regular expression string containing only letters a-z or .. A . means it can represent any one letter.

For example:
```
addWord("bad")
addWord("dad")
addWord("mad")
search("pad") -> false
search("bad") -> true
search(".ad") -> true
search("b..") -> true
```
**Note:**  
You may assume that all words are consist of lowercase letters a-z.

click to show hint.

You should be familiar with how a Trie works. If not, please work on this problem: Implement Trie (Prefix Tree) first.

---

* Difficulty: Medium
* Topics: Backtracking, Trie, Design
* Companies: Facebook
* LeetCode: [211. Add and Search Word - Data structure design](https://leetcode.com/problems/add-and-search-word-data-structure-design/description/)
