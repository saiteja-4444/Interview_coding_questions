<h1 align='center'>Reversing of  a String</h1> 

## Using slicing :

``` python
string = 'hello'
new_string = string[::-1]
print(new_string)
```

## Using a loop :
``` python
def reverse_string(s):
    reversed_str = ""
    for char in s:
        reversed_str = char + reversed_str
    return reversed_str

my_string = "Hello World"
print(reverse_string(my_string))  # Output: "dlroW olleH"
```
