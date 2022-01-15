### 1: In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.
* 			-> Expression
'hello' 	-> Value
-87.8  		-> Value
- 			-> Expression
/ 			-> Expression
+			-> Expression
6 			-> Value

### 2. What is the difference between string and variable?
A String is a datatype (an array of characters) and Variable is an entity to store values that can be used for later. Variables are stored in memory. 
### 3. Describe three different data types.
Int – Integer datatype describes the integer type data (-2147483648 through 2147483647)
Float – Decimal datatype describes the floating-point numbers (1.04, 2.0512)
Bool - Boolean datatype - True or false
### 4. What is an expression made up of? What do all expressions do?
An expression is made of mathematical operators that can perform operations on operands. Every expression leads to a value.
### 5. This assignment statements, like spam = 10. What is the difference between an expression and a statement?
An expression evaluates the mathematical operations while statements are something that helps us to create valid instructions.
### 6. After running the following code, what does the variable bacon contain?
        bacon = 22
        bacon + 1

22
### 7. What should the values of the following two terms be?
'spam' + 'spamspam'

```python
'spam' + 'spamspam'
```




    'spamspamspam'


'spam'*3

```python
'spam'*3
```




    'spamspamspam'



### 8. Why is eggs a valid variable name while 100 is invalid?
Because python does not allow the naming of variable to start with number.
Some valid naming conventions are: 
a 
las
As_12
Asf1
### 9. What three functions can be used to get the integer, floating-point number, or string version of a value?
int(), float(), str()
### 10. Why does this expression cause an error? How can you fix it?
'I have eaten ' + 99 + ' burritos.'We cannot concatenate an ‘int’ datatype directly to ‘str’. We need to either type cast the integer to string or add quotes to it.

‘I have eaten’ + str(99) + ‘burritos’
‘I have eaten’ + ‘99’ + ‘burritos’

```python
'I have eaten' + str(99) + 'burritos'
```




    'I have eaten99burritos'




```python

```
