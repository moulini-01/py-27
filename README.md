# py-27
printing even indexing charecters
def print_even(s):
    for i in range (len(s)):
        if(i%2==0):
            print(s[i],end="")
print_even("python")
