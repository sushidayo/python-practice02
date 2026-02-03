# python-practice02
def gen(maxnum):     for i in range(maxnum):         yield i          g = gen(7) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) ) print( next (g) )  g = (x for x in range(7) )  t = [x for x in range(9) ]

def gen (maxium):
    base = 0
    i = 0
    while i < maxium:
        o = (yield base + i)
        
        if o  is not None:
            base = o
        else:
            i += 1

g= gen(10)
print( next(g) )
print( next(g) )
g.send(10)
print( next(g) )
print( next(g) )
g.send(0)
print( next(g) )
print( next(g) )
print( next(g) )


#初週分の余白を表示
print('     '* w, end='')

#日付を順番に表示
for day in range(d) :
    if (w % 7 == 0) and (w >= 7):
        print()
    print('{:5d}'.format(day+1), end ='')
    w += 1
    
#プログラムの実行
year = 2026
month = 2
days = getMonthDays(year, month)
printCalendar(year, month, days)
