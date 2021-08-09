<div>
<a href="https://github.com/SergioO21/monty">
  <img align="right" src="https://i.pinimg.com/originals/b0/45/5b/b0455b3b8446ce5c3acbd03f7c28bcfe.gif" width="300" height="250"/>
</a>
<a href="https://www.holbertonschool.com/">
  <img align="center" src="https://www.holbertonschool.com/holberton-logo.png"/>
</a>
</div>


<h1> FIX MY CODE</h1>

<b>Fix my code</b> is a new type of project, in which I will jump to an existing code base and fix it.

I not recode everything, I just fix it!

This repository [0x00-Fix_My_Code_Challenge](https://intranet.hbtn.io/rltoken/V1o_qyMWRS-uCTQX1t5VrQ "0x00-Fix_My_Code_Challenge") has the code base to fix.


<h2>FizzBuzz - Python</h2>
<p>Something is going wrong ...</p>

```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```
`15` should print `FizzBuzz` not `Fizz`

<h3>Fixed</h3>

```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 FizzBuzz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 FizzBuzz 46 47 Fizz 49 Buzz
$
```


<h2>Print square - JavaScript</h2>
<p>Something is going wrong ...</p>

```
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
```
`./1-print_square.js 10` should print a square of size 10 …

<h3>Fixed</h3>

```
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
##########
##########
##########
##########
##########
##########
##########
##########
##########
##########
$
```

<h2>Sort - Ruby</h2>
<p>Something is going wrong ...</p>

```
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$
```

<h3>Fixed</h3>

```
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
-9
-1
2
9
12
31
32
41
$
```


<h2>User password - Python</h2>
<p>Something is going wrong ...</p>

```
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```

<h3>Fixed</h3>

```
$ ./3-user.py 
Test User
$
```


<h2>Double linked list - C</h2>
<p>Something is going wrong ...</p>

```
$ gcc -Wall -pedantic -Werror -Wextra main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```
It doesn’t look right …

<h3>Fixed</h3>

```
$ gcc -Wall -pedantic -Werror -Wextra main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
402
1024
-----------------
1
2
3
4
402
1024
-----------------
2
3
4
402
1024
-----------------
3
4
402
1024
-----------------
4
402
1024
-----------------
402
1024
-----------------
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```


<h2>Author</h2>

 -  ***Sergio Orejarena*** / [Github](https://github.com/SergioO21) - [Twitter](https://twitter.com/SergioOR21) .

> Finished 09 / 08 / 2021
