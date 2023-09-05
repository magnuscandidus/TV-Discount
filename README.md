# TV-Discount
# cook your dish here
TV =int(input())
for V in range(TV):
  A,B,C,D = map(int,input().split())
  TV1 = A-C
  TV2 = B-D
  if TV1 > TV2: print("second")
  elif TV2 > TV1:print("first")
  else:print("any")
