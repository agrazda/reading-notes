A while loop
never ends until a statement it false

A 'for' Loop
if continuously tru an action is taken - ex. 

increment i

for (var i=0; i<=12; i = i +1){
    consol.log()
}

arithetic operators


Consol.log (answer to the question)

x<y: less than


## Comparison Operators Evaluating Condiitions
- ==
  > equals to
- ===
  > Strict equal to
- !=
  > is not equal to 
- !==
  > strict not equal to
- (>) 
  > greater than 
- (>=)
  > greater than or equal to
- (<) 
  > less than 
- (<=)
  > less than or equal to
- x++
  > increment by 1
- xx--
  > decriment by 1

## Logical Operations

  Logical operators allow you to comare the results of more than one comarison operator.

- && =Logical and
  > This operation tests more than one operation (Both have to be true)
    - ((2 <5 ) && (3 >= 2)) returns true
- || =Logical or
  > This operatior tests at least one condition
    - ((2 < 5) || (2 < 1)) returns true
- ! = logical not
  > This operator takes a single boolean value and inverts it
    - !(2 < 1)

### Short-Circuit Evaluations  
Logical expressions are evaluated let to right. 
If the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition.  

 - false && anything  ( there isn o pint continuing to determine the other result)  

 - True || anything (There is no pint continuing because at lease one of the calues is true)

 ## Loops

 - For
   > if you need to run code a specific number of times, use a **for** loop

 - While
   > if you do not know how many times the code should run, you can use a **while** loop.

 - Do While
   > the do...while loop is very similar to the while loop, but has one key diff. It will always run the statements inside the curly braces at least once, even if the condition evaluates to false  

   keyword          condition(counter)      opening curly brace
      for