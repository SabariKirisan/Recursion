## Print Name N time (c++)

Print Name N times without the loop.

## Example
Input: 5

Output: GFG GFG GFG GFG GFG

## PROGRAM:(Main.cpp)
```
class Solution {
  public:
    void printGfg(int N) 
    {
        if(N==0) return;
        cout<<"GFG"<<" ";
        printGfg(N-1);
    }
};
```
## Complexity
- Time complexity : O(N)

- Space complexity : O(N)
