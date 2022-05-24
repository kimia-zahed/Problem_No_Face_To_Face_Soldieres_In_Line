# Problem_No_Face_To_Face_Soldieres_In_Line
A number of soldiers standing in a line who are directed randomly change their direction until there are no face to face soldiers 

## What is exactly the problem?
A number of soldiers or a standing next to each other in a line the like this " > > > > > > > > >  " 

First time they hear the whistle each soldier takes a random direction like this " < > > > < < > < < "

Each two soldiers can only be in these three positions : back-to-back " < > ", face-to-face " > < ", back-to-face "> >" 

Afterwards in each step soldiers who are face to face flip 180 degrees.

#### Qustion is: how many steps are needed until there are no face-to-face soldiers ?

## Hwo do we solve this ?
In this code we have simulated the process with python  from 10 to n soldiers (you can define n ) and  counted the number of tries for  10 times.

Next the avrage of trying number is calculated.

Finaly it is undrestod :

n = number of soldiers 

step = number of triies 

#### step = 0.5 * n
![Test Image 7](https://github.com/kimia-zahed/Problem_No_Face_To_Face_Soldieres_In_Line/blob/main/numberOfsoldiers.png)
