# This is a pure python function to do all basic functions in maths (+,-,*,/,//)

- Source Code -

def mathsfunction(x,y):
    print(''' What Function Do you Want To Perform ?
1 - Addition
2 - Subtraction
3 - Multiplication
4 - Division
5 - Floor Division
6 - Expoent Power
NOTE : NUMBERS WILL BE ACTED PROPORTIONAL TO THE X AND Y VALUES''')

    func = int(input('>>> '))
    if func == 1:
        return x + y
    elif func == 2:
        return x - y
    elif func == 3:
        return x * y
    elif func == 4:
        return x / y
    elif func == 5:
        return x // y
    elif func == 6:
        return x ** y
