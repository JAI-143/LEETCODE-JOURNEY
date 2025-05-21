class Solution:
    def setZeroes(self, matrix: List[List[int]]) -> None:
        l1=[]
        l2=[]
        for j in range(len(matrix)):
            for k in range(len(matrix[0])):
                if matrix[j][k]==0:
                    l1.append(k)
                    l2.append(j)
        for j in range(len(matrix)):
            for k in range(len(matrix[0])):
                if j in l2:
                    matrix[j][k]=0
                elif k in l1:
                    matrix[j][k]=0
