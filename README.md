<div align="center">

## Easy Math


</div>

### Description

Do math, add, subtract, multiply, divide
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Demian Net](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/demian-net.md)
**Level**          |Intermediate
**User Rating**    |3.5 (14 globes from 4 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Math/ Dates](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math-dates__1-37.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/demian-net-easy-math__1-6966/archive/master.zip)

### API Declarations

```
Option Explicit
 Public Sub Multiply(X As Integer, Y As Integer)
   Dim Z
   Z = X * Y
   Text3.Text = Str(Z)
 End Sub
 Public Sub Subtract(X As Integer, Y As Integer)
   Dim Z
   Z = X - Y
   Text3.Text = Str(Z)
 End Sub
 Public Sub Add(X As Integer, Y As Integer)
   Dim Z
   Z = X + Y
   Text3.Text = Str(Z)
 End Sub
 Public Sub Divide(X As Integer, Y As Integer)
   Dim Z
   Z = X / Y
   Text3.Text = Str(Z)
 End Sub
```


### Source Code

```
'Make a Command1
 'Make a Text1
 'Make a Text2
 'Make a Text3 (Locked)
 'Add
 Private Sub Command1_Click()
 Add Text1, Text2
 End Sub
 'Subtract
 Private Sub Command1_Click()
 Subtract Text1, Text2
 End Sub
 'Multiply
 Private Sub Command1_Click()
 Multiply Text1, Text2
 End Sub
 'Divide
 Private Sub Command1_Click()
 Divide Text1, Text2
 End Sub
```

