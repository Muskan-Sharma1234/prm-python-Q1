# prm-python-Q1
def find_len(list1):
    length = len(list1)
    list1.sort()
    print(list1[length-1])
    print(list1[0])
    print(list1[length-2])
    print(list1[1])
list1=[1,2,3,4,5,6]
Largest = find_len(list1)
