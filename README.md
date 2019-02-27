# linear-search
def linear_search(A,K):
   for i in A:
      if i==k:
        return 'value found{}'.format(i)
   else:
        return 'value not found'
a=[1,32,4,5,7,6]
a.sort()
num=int(input('enter the value of linear seaarch'))
print(linear_search(a,num))
