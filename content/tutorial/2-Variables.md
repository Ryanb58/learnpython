## Numbers

Lets pop into an interactive shell and type the following:

```
4 * 7
```

You should see something similar to the following:

```
>>> 4 * 7
28
```

Awesome! You just did multiplication and the product(result) was printed below
your input.

The astrisk between the four and the seven is called an operator in python.
Operators are normally very intuitive for example: `+`, `-`, and `/` are all operators. In fact they match up to the actions of `adding`, `subtracting`, and `dividing`.

Lets try them out:

```
>>> 4 + 7
11
>>> 4 - 7
-3
>>> 8 / 2
4.0
```

Neato! That seemed to of worked pretty well, but what about other operators?
Sadly this page would become cluttered if I were to include every operator on
it. Yet luckily for you there is documentation. The python docs are a fantastic
resource when you need to perform some sort of action but are unsure how. Lets
visit their documentation now:

[https://docs.python.org/3/library/operator.html#mapping-operators-to-functions](https://docs.python.org/3/library/operator.html#mapping-operators-to-functions)

The link above is a direct link to the operators table that python includes.
So now for the challenge:

Take 4 to the power of 7. Your result should be: 16384

Answer:

```
>>> 4**7
16384
```

## Variables

Now that you have learned how to use operators in python, lets dive into the
use of variables. You can think of a variable as an alias or reference for the
result of the operator.

For example if you run this code:

```
>>> result = 4 * 7
```

You will notice that the answer of 4 times 7 did not print out on the next
line. This is because the product was stored in a variable named `result`.
To see the contents of that variable just type in the name on another line.

```
>>> result
28
```

Now everytime you need the number 28 you can simply interject the variable
`result`.

```
>>> result - 10
18
```

Great job, you just used a variable in your code. Although if you thought that
the variable `result` would reference the number 18 now, you would be wrong.
That is because we didn't assign the variable to the result of the equation
we wrote in our code. Try typing in `result` now and it should output `28`
still.


## Strings

How about adding some test into the mix.