
# **LOTTO GAME**

This program generates up to 5 lottery tickets.

You will be able to choose the numbers played for each ticket, the wheel or wheels and the type of play you want to make.

The program will generate the numbers to play.

But... let's start!

## Index
1. [How many ticket](#nTicket)
2. [How many numbers](#nNumbers)
3. [Wheels](#wheels)
4. [Type of bet](#type)
5. [price amount played](#prices)
6. [More Tickets](#more)
7. [Print tickets](#print)
8. [Fake Extraction](#fake)
9. [Total Win!](#money)
---

Choose how many ticket to play from 1 to 5 <a name="nTicket"></a>

```
                     Lotto Game!

How many tickets do you want to generate? ( from 1 to 5 )

> 
```
Now choose how many numbers you want to play on the first ticket <a name="nNumbers"></a>
```

                      TICKET #1

How many numbers do you want to play? ( form 1 to 10 )

> 
```
Select the desired wheels: <a name="wheels"></a>
* if you select 'Tutte' you will go directly to choosing the type of bet.
* if you select another wheel you will no longer have the option to select 'Tutte'
```
Which wheel do you want to play?

1) Bari
2) Cagliari
3) Firenze
4) Genova
5) Milano
6) Napoli
7) Palermo
8) Roma
9) Torino
10) Venezia
11) Tutte
 
n) Next
```
You can choose the wheels you want, they will be displayed above, those already chosen will automatically be removed from the list.

 When you're ready press 'n' to continue
```
===========================
Firenze <> Napoli <> Milano
===========================

Which wheel do you want to play?

1) Bari
2) Cagliari
3) Genova
4) Palermo
5) Roma
6) Torino
7) Venezia
 
n) Next
```
Choose the type of bet: <a name="type"></a>
* you can choose as many as you like,
* if you have played less than 5 numbers, the higher bets will not be displayed in the menu. Example: if you play 3 numbers you will not see 'Quaterna' and 'Cinquina'


```
What type of bet do you want to place?

1) Estratto
2) Ambo
3) Terno
4) Quaterna
5) Cinquina
 
n) Next
```
As in the previous menu, those selected will no longer be available for selection
```
=================
Terno <> Cinquina
=================

What type of bet do you want to place?

1) Estratto
2) Ambo
3) Quaterna
 
n) Next
```
Enter the amount you want to play for each type of win you have chosen <a name="prices"></a>
```
=================================================
Estratto <> Ambo <> Terno <> Quaterna <> Cinquina
=================================================

Indicates the amount for each type of bet

Estratto ??? 5
Ambo ??? 5
Terno ??? 2
Quaterna ??? 2
Cinquina ??? 1
```
When you're ready will be generated the second ticket if you have chosen more than 1. <a name="more"></a>

At the top you will be shown the summary of the first ticket.


Repeat the process for all the tickets you want to generate 
```
Ticket #1 : 5 numbers played on the Firenze,Napoli,Milano wheel with Terno,Cinquina


                      TICKET #2

How many numbers do you want to play? ( form 1 to 10 )

> 
```
Once generated, they will all be printed on the monitor, the ticket.txt file will also be created to facilitate printing, an example below <a name="print"></a>
```
+==========================================================+
|                   LOTTO GAME TICKET #1 **??? 6**           |
+==========================================================+
|                 Firenze  Napoli  Milano                  |
+==========================================================+
|                     Terno  Cinquina                      |
+==========================================================+
|                      ??? 5     ??? 1                         |
+==========================================================+
|                  35 - 52 - 69 - 73 - 27                  |
+==========================================================+


+==========================================================+
|                   LOTTO GAME TICKET #2 **??? 1**           |
+==========================================================+
|                         Venezia                          |
+==========================================================+
|                         Cinquina                         |
+==========================================================+
|                           ??? 1                            |
+==========================================================+
|      17 - 6 - 13 - 70 - 42 - 37 - 64 - 35 - 22 - 44      |
+==========================================================+
```
A simulated extraction of all wheels will also be generated. <a name="fake"></a>

The table indicates all the matches between your numbers and those generated. 

#1, #2, etc.. is the number of your ticket and then the type of winnings made
```
                 FAKE EXTRACTIONS                          TICKET WIN                    
+==========+==========================+==================================================+
|   Bari   |  10 - 25 - 73 - 30 - 40  |                   #1 1 Estratto                  |
+==========+==========================+==================================================+
| Cagliari |  22 - 36 - 15 - 40 - 39  |                                                  |
+==========+==========================+==================================================+
| Firenze  |  62 - 63 - 55 - 40 - 20  |               #1 2 Estratto-1 Ambo               |
+==========+==========================+==================================================+
|  Genova  |  10 - 17 - 86 - 61 - 82  |                   #1 1 Estratto                  |
+==========+==========================+==================================================+
|  Milano  |  34 - 65 - 31 - 48 - 32  |                                                  |
+==========+==========================+==================================================+
|  Napoli  |  1 - 64 - 47 - 19 - 85   |               #1 2 Estratto-1 Ambo               |
+==========+==========================+==================================================+
| Palermo  |  17 - 48 - 57 - 60 - 80  |                   #1 1 Estratto                  |
+==========+==========================+==================================================+
|   Roma   |  11 - 40 - 67 - 51 - 15  |                                                  |
+==========+==========================+==================================================+
|  Torino  |  37 - 12 - 24 - 60 - 54  |                                                  |
+==========+==========================+==================================================+
| Venezia  |  41 - 87 - 73 - 2 - 88   |                                                  |
+==========+==========================+==================================================+
```
Finally the amounts won for each ticket, the totals won and the total invested are shown <a name="money"></a>
```
Total winnings already detaxed by 8%:

TICKET #1 WIN ??? 4.1 - Paid for : 2 Estratto 1 Ambo  on Firenze

Total winnings: ??? 4.1
Total invested: ??? 12
```
Good fun ! ????