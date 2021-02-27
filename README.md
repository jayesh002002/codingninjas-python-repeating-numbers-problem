# codingninjas-python-repeating-numbers-problem
question - input: 5
           output: 1
                   23 
                   4567
                   89123456
                   7891234567891234
                   
error in solution - 
code:
n=int(input()) 
x=1
for i in range(0,n):
	for j in range(0,(2**i)):
		if(x<10):
			print(x,end='')
			x=x+1
		else:
			x=1
	print()
  
  input:5
  output:
  1
  23
  4567
  8912345
  67891234567891
  Incorrect Output
  
    new to github, pls help
