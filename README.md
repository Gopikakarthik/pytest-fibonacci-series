# pytest python program for fibonacci series
# DATE:8/11/24
# REGISTER NUMBER:212222040046
# Aim:
To write a python program for Fibonacci Series and test the test cases using Pytest.
# Algorithm:
1.Write the python program for addition of two numbers

2.Make sure that function name should be “def test_*():” and the line to be tested should have assert keyword at the beginning 

3.Write some test cases for to be tested and save it as “test_add.py”. 

4.Open command prompt and change the directory to where pytest and program is saved and type “pytest test_add.py” and run it.
# program:
```
def fibR(n):
if n==1 or n==2:
return 1
return fibR(n-1)+fibR(n-2)
def test_fib_1_equals_1():
assert fibR(1) == 1
def test_fib_2_equals_1():
assert fibR(2) == 1
def test_fib_6_equals_8():
assert fibR(6) == 7
```
# output:
![Screenshot 2024-11-14 213817](https://github.com/user-attachments/assets/df8723e6-afd9-46f7-83f6-0e116f2375a7)
# Result:
Thus, the python program for addition is tested using pytest and executed and output is verified
successfully.





