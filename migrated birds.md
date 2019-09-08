# hackerrank-problem-solveing-python
n=int(input())
b=list(map(int,input().rstrip().split()))
fr= [0, 0, 0, 0, 0, 0]    
for i in range(n):
    fr[b[i]]+=1
    
  
print(fr.index(max(fr)))

