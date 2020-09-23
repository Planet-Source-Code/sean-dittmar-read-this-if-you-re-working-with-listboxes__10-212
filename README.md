<div align="center">

## Read this if you're working with listboxes\.\.\.


</div>

### Description

This explains why the ListBox's Clear method does not work anymore and explains it's replacement
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Sean Dittmar](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sean-dittmar.md)
**Level**          |Beginner
**User Rating**    |4.0 (12 globes from 3 users)
**Compatibility**  |VB\.NET, ASP\.NET
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__10-33.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sean-dittmar-read-this-if-you-re-working-with-listboxes__10-212/archive/master.zip)





### Source Code

```
If you want to clear a listbox,
you call the method ListBox.Clear, right?
Not in VB7, I found this out the frustrating
way. To clear a listbox, you need to use
the listbox's item collection's Clear
method. Let's recap:
VB6 - ListBox.Clear
VB7 - ListBox.Items.Clear
```

