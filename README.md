# python-practice02
def gen(maxnum):     for i in range(maxnum):         yield i          g = gen(7) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) )  g = (x for x in range(7) )  t = [x for x in range(9) ]
