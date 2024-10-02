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
Using recursion :
``` python
def reverse_string(s):
    if len(s) == 0:
        return s
    else:
        return reverse_string(s[1:]) + s[0]

my_string = "Hello World"
print(reverse_string(my_string))  # Output: "dlroW olleH"
```

Using the reversed() function:
``` python
my_string = "Hello World"
reversed_string = ''.join(reversed(my_string))
print(reversed_string)  # Output: "dlroW olleH"
```
