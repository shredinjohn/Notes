
### Maximum of numbers 

- Use ternary operators 
```c
max = a>b?a:b;
```

## Sentence as input

taking a line as input, you can use `scanf("%[^\n]%*c", s);`

```c
scanf("%[^\n]%*c",&sen);
```
➡️  The statement: `scanf("%[^\n]%*c", s);` will not work because the last statement will read a newline character, `\n`, from the previous line. This can be handled in a variety of ways. One way is to use `scanf("\n");` before the last statement.

