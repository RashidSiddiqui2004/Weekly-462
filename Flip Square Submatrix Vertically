class Solution {
public:
    vector<vector<int>> reverseSubmatrix(vector<vector<int>>& grid, int x, int y, int k) {
        int x1 = x+k, y1=y+k, ptr=1;
        vector<vector<int>> temp = grid;
        for(int i=x;i<x1;i++){
            for(int j=y;j<y1;j++){
                grid[i][j] = temp[x1-ptr][j];
            }
            ptr++;
        }
        return grid;
    }
};
