# Lets-Find-in-the-integer-list
def blackjack(a,x,y,z):
    xi=a.index(x)
    zi=a.index(z)
    if(a[xi:zi+1]==[x,y,z]):
        return True
    else:
        return False
