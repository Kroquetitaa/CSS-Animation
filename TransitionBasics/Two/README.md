<table style="text-align:center">
<tr>
<td>
<strong>transition-duration</strong>
</td>
<td> Tiempo de duracion que tarda en realizar la transicion</td>
</tr>
<tr>
<td>
<strong>transition-delay</strong>
</td>
<td> Tiempo que tardará en iniciar a realizar la transicion</td>
</tr>
<td>
<strong>transition-timing-function</strong>
</td>
<td>Como se va a realizar el movimiento de la transicion</td>
</tr>
</table>

```css
.ball{
    width: 125px;
    height: 128px;
    position: absolute;
    top: 0;
    left: 0;
    transition-property: left;
    transition-duration: 3s;
    transition-delay: 1s;
    transition-timing-function: linear;
}
```