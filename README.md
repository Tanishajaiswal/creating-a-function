# creating-a-function.py
by tanisha
str=input("please enter a string")
def most_frequent(letter):
    d=dict()
    for key in letter:
        if key not in d:
            d[key]=1
        else:
            d[key]= d[key]+1
    return d
print(most_frequent(str))
