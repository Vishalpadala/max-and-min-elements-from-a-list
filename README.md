# max-and-min-elements-from-a-list
l=[ ] n=int(input('enter number of elements: ')) for i in range(n):        e=int(input("values: "))        l.append(e) max=l[0] min=l[0] for i in range(1,n):         if l[i]>max:             max=l[i] print(max) for i in range(1,n):     if l[i]&lt;min:         min=l[i] print(min)
