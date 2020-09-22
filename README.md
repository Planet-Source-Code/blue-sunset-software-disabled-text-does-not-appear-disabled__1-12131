<div align="center">

## Disabled Text Does Not Appear Disabled


</div>

### Description

This tip is on the off chance you want to break with GUI standards and show a disabled text box (or other control) without the typical grayed out "disabled" look.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Blue Sunset Software](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/blue-sunset-software.md)
**Level**          |Intermediate
**User Rating**    |4.8 (19 globes from 4 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/blue-sunset-software-disabled-text-does-not-appear-disabled__1-12131/archive/master.zip)





### Source Code

```
Because of GUI standards, you wouldn't want to use this technic very often. But there are circumstance in which you want to present data without allowing the user editing privileges.
Just using the locking mechanism still allows the user to to click in the control, highlight the text and shows up in the tab order. Here is a better way.
Add a frame to your form. Set the border style to 0 - None. Place the text box in the frame (with with its accompaning label) at the top of the frame. Size the frame to show just the text box and its label. Now you can control the enable/disable property on the frame.
The text box and label appear normal but it won't allow the user the click in the box, tab to the control or edit data when the frame is disabled. To allow the user access, just enable the frame.
```

