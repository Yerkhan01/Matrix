import random
n = int(input("Columns: "))
m = int(input("Line: "))
def form_matrix(n,m):
    matrix = [[random.randint(-50,50) for i in range(n)] for j in range(m)]
    print('Matrix: ')
    for i in matrix:
        for j in i:
            print(j,end = '\t')
        print()
    return matrix

def execute(matrix):
    k = [[x[i] for x in matrix] for i in range(len(matrix[0])) ]
    for i in k:
        for j in i:
            if j*-1 in i and j!=0:
                return k.index(i)+1
    return 0

form = form_matrix(n,m)
execute = execute(form)
print("Column: ", execute)
