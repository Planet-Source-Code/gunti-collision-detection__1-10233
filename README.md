<div align="center">

## Collision Detection


</div>

### Description

This is an example in how to proove if there is a collision between object A and object B. There are already some codes like this here, but all i've seen so far, did not work very well, so here is my solution...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[gunti](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/gunti.md)
**Level**          |Intermediate
**User Rating**    |3.2 (16 globes from 5 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Games](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/games__1-38.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/gunti-collision-detection__1-10233/archive/master.zip)





### Source Code

```
if A.left + A.width > B.left then
 if A.left < B.left + B.width then
 if A.top < B.top + B.height then
 if A.top + A.height > B.top then
 'Collission Detected.
 'further actions here
 MsgBox "collission detected"
 else
 'no collission
 'further actions here
 MsgBox "no collision"
 end if
 end if
 end if
end if
```

