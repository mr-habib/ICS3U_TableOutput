# ICS3U_TableOutput

Your task is to, well, output a table ... based on the user's input.

The program will prompt a user to enter rows of a table, each peiece of data being separated by spaces, and it's your job to print them out to the screen in a nice table format.

## Example Interaction
```
>> Enter a row: Name Job Student_Number
>> Enter a row: Kevin Student 12332
>> Enter a row: Emmanuel Philosopher 43321
>> Enter a row: Philomena Saint 4552112
>> Enter a row: quit
Name      Job         Student_Number
Kevin     Student              12332
Emmanuel  Philosopher          43321
Philomena Saint              4552112
```

Some things to note:
You can use variables in the fstring format specifiers:
```
print(f'{var_name:{len(var_name)+1}')
```
Will give the text a padding of one more than the length of the word.

You will need to use a while loop to loop untilthe user presses quit, otherwise keep appending the list with elements and print them accordingly. The trick to this is that each column has a text width of one more than the longest word in the column.


