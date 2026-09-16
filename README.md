# 24BDA70191-EXP-2.3.1-CC-GROUP-A
class Solution {
public:
    int addDigits(int num) {
        if (num == 0) return 0;
        return 1 + (num - 1) % 9;
    }
};
