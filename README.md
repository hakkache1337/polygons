# Polygons

Polygons is a tiny C program developed in my free time at 42 school for generating all polygons from 1 to 360 sides.
<img align="center" src="http://i.imgur.com/y2sxbI0.png" width="100%" />
Several options are available (see [Keyboard shortcuts](https://github.com/BenjaminSouchet/Polygons/blob/master/README.md#keyboard-shortcuts) section for more infos) :
* Zoom and unzoom
* Rotate the polygon
* Edit the shape of the polygon
* Edit the position of all odd and/or even vertex
* Choose from edge or fill for the display of the poly
* Navigate between polygons with 1 to 360 sides

## Install & launch
```bash
git clone https://github.com/BenjaminSouchet/Polygons.git ~/Polygons
cd ~/Polygons && ./polygons 5
```
You can also launch the program with a parameter. It's the number of sides you want for the polygon at the execution of the program. This parameter as to be between 1 and 360 included.<br />
Exemple :
```bash
./polygons 10
```

## Keyboard shortcuts

<table width="100%">
<thead>
<tr>
<td width="100%" height="60px" align="center" cellpadding="0">
<strong>Description</strong>
</td>
<td width="100%" align="center" cellpadding="0">
<span style="width:50px">&nbsp;</span><strong>Key(s)</strong><span style="width:50px">&nbsp;</span>
</td>
</tr>
</thead>
<tbody>
<tr>
<td valign="top" height="30px">Close the program (aka quit/exit)</td>
<td valign="top" align="center"><kbd>&nbsp;esc&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Reset all the changes made since the beginning</td>
<td valign="top" align="center"><kbd>&nbsp;clear&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Increase the global size of the polygon (aka zoom)</td>
<td valign="top" align="center"><kbd>&nbsp;+&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Decrease the global size of the polygon (aka unzoom)</td>
<td valign="top" align="center"><kbd>&nbsp;-&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Increase the height of the polygon (aka height stretch)</td>
<td valign="top" align="center"><kbd>&nbsp;▲&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Decrease the height of the polygon (aka height shrink)</td>
<td valign="top" align="center"><kbd>&nbsp;▼&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Increase the width of the polygon (aka width stretch)</td>
<td valign="top" align="center"><kbd>&nbsp;►&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Decrease the width of the polygon (aka width shrink)</td>
<td valign="top" align="center"><kbd>&nbsp;◄&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Fill or unfill the polygon</td>
<td valign="top" align="center"><kbd>&nbsp;shift&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Increase the position of all odd points of the polygon</td>
<td valign="top" align="center"><kbd>&nbsp;W&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Decrease the position of all odd points of the polygon</td>
<td valign="top" align="center"><kbd>&nbsp;Q&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Increase the position of all even points of the polygon</td>
<td valign="top" align="center"><kbd>&nbsp;S&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Decrease the position of all even points of the polygon</td>
<td valign="top" align="center"><kbd>&nbsp;A&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Clockwise rotation of the polygon</td>
<td valign="top" align="center"><kbd>&nbsp;X&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Counter clockwise rotation of the polygon</td>
<td valign="top" align="center"><kbd>&nbsp;Z&nbsp;</kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Previous polygon</td>
<td valign="top" align="center"><kbd><center>&nbsp;page&nbsp;<br /> up</center></kbd></td>
</tr>
<tr>
<td valign="top" height="30px">Next polygon</td>
<td valign="top" align="center"><kbd>&nbsp;page&nbsp;<br /> down</kbd></td>
</tr>
</tbody>
</table>

## Contact & contribute
If you want to contact me, or fix/improve Polygons, just send me a mail at **bsouchet@student.42.fr**
