# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

#ctf 

- List
- of 
- Things
	- one
	- two
  
```c
//Luhn's Algorithm i.e. the checkSum in this case

int Luhn_Algo(long num)

{
    int length = get_length(num);
    int last;
    int secondLast;
    int sum1 = 0; //not doubled sum
    int sum2 = 0; //doubled sum
    int x = 0;

    while (num > 0)
    {
        //calculating not doubled sum
        last = num%10;
        num = num/10;
        sum1 += last;
        
        //calculating doubled sum
        secondLast = num%10;
        num = num/10;
        x = 2* secondLast;
        if (x>=10)
        {
            x = 1+ x%10;
        }
        sum2 = sum2 + x;
    }
    int totalSum = sum1 + sum2;
    return totalSum;

}

```



**This is the bold text** with normal coloured text at the side 
_this is italics_
==This is highlighted==
**_bold italics_**
[[Operating Systems]]

`single quotes`

$$
\begin{gather}
E=m*c^2\\
\text{math equations}
\end{gather}
$$


| table        | test |
| ------------ | ---- |
| one          | 1215 |
| two<br>three |      |
| four         |      |



> [!NOTE] Callout test
> Lorem impus



> quote test
> by me 


- [ ] task
- [ ] list\
- [ ] will
- [ ] look
	- [ ] like 
	- [x] this 
	- [ ] 









| Process | AT  | BT  |
| ------- | --- | --- |
| P1      | 0   | 5   |
| P2      | 1   | 10  |
| P3      | 2   | 14  |

| P1<br>0 -> 5 | P2<br>5 --> 15 | P3<br>15 --> 29 |
| ------------ | -------------- | --------------- |







