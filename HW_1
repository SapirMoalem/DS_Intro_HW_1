


def my_func(x1,x2,x3):
    ''' Trying to make the variable we get to float
    try:
        x1 = float(x1)
        x2 = float(x2)
        x3 = float(x3)
    except:
        print("Error: parameters should be float")
        return
    '''

    if type(x1) != float or type(x2) != float or type(x3) != float:
        print("Error: parameters should be float")
        return

    if (x1 + x2 + x3) == 0:
        print( "Not a number – denominator equals zero")
        return

    up = (x1+x2+x3)*(x2+x3)*x3
    down = x1+x2+x3
    num = up/down

    return num



'''
print(my_func(0., 1., 1.))
print(my_func(0., 1., 'g'))
print(my_func(0., -1., 1.))
print(my_func(2.0, 1., 1.))
print(my_func(1., 1., 1.), " = 2 ")
print(my_func(1., 2., 3.) ,"= 15")
print(my_func(2.0, 2.0, 2.0))
'''








def convert(hours,minutes):

    if hours < 0 or minutes < 0:
        print("Input error!")
        return


    hours = hours*3600
    minutes = minutes*60

    return hours+minutes

'''
assert 3780 == convert(1, 3)
assert 3600 == convert(1, 0)
assert 180 == convert(0, 3)
assert 0 == convert(0, 0)
assert convert(1, 30) == convert(1.5,0)
assert convert(1, 45) == convert(1.75,0)
assert 30 == convert(0,0.5)
assert 60 == convert(0,0.5) + convert(0,0.5)
assert convert(10,0) == convert(3,300) + convert(2,0)
assert None == convert(-1,3)
assert None == convert(0,-10)
# assert None == convert("f",-10)
# assert None == convert("f",-10)
print(" 1,3 = 3780,",convert(1, 3))
'''



