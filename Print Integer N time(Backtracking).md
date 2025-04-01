## Print Integer N time(Backtracking) (c++)

You are given an integer ‘n’.

Your task is to return an array containing integers from 1 to ‘n’ (in increasing order) without using loops.

## Example
Input: ‘n’ = 5

Output: 1 2 3 4 5

Explanation: An array containing integers from ‘1’ to ‘n’ is [1, 2, 3, 4, 5].

## PROGRAM:(Main.cpp)
```
vector<int> printNos(int x) 
{
    if(x==0) return{};
    vector<int> res=printNos(x-1);
    res.push_back(x);
    return res;
    
}
```
## Complexity
- Time complexity : O(N)

- Space complexity : O(N)
