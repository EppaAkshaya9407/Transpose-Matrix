# Transpose-Matrix
class Solution:
    def transpose(self, matrix: list[list[int]]) -> list[list[int]]:
        n=len(matrix)
        m=len(matrix[0])
        r=[]
        for i in range(m):
            r1=[]
            for j in range(n):
                r1.append(matrix[j][i])
            r.append(r1)
        return r
