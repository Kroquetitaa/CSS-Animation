
<table style="text-align:center">
<tr>
<td><strong>margin</strong></td>
<td>Cantidad de margen que dejamos</td>
</tr>
<tr>
<td><strong>padding</strong></td>
<td>"Relleno" que dejamos</td>
</tr>
</table>

```css
*{
    margin: 0;
    padding: 0;
}
```

<table style="text-align:center">
<tr>
<td><strong>position</strong></td>
<td>Posicion de nuestra etiqueta ( absolute o relative )</td>
</tr>
<tr>
<td><strong>width</strong></td>
<td>Ancho que vamos a ocupar ( normalmente usamos % )</td>
</tr>
<tr>
<td><strong>height</strong></td>
<td>Alto que vamos a ocupar ( normalmente usaremos vh )</td>
</tr>
<tr>
<td><strong>background-color</strong></td>
<td>Color de fondo</td>
</tr>
<tr>
<td><strong>font-family</strong></td>
<td>Fuente que vamos a utilizar para las letras</td>
</tr>
</table>

```css
body{
    position: relative;
    width: 100%;
    height: 100vh;
    background-color: #111;
    font-family: sans-serif;
}
```

<table style="text-align:center">
<tr>
<td><strong>font-size</strong></td>
<td>Tamaño de nuestra fuente ( normalmente en px ) </td>
</tr>
<tr>
<td><strong>text-align</strong></td>
<td> Hacia donde centramos nuestro texto </td>
</tr>
<tr>
<td><strong>line-height</strong></td>
<td>Establecer la altura por linea</td>
</tr>
<tr>
<td><strong>top</strong></td>
<td>Espacio que dejamos en la altura ( normalmente en % )</td>
</tr>
<tr>
<td><strong>left</strong></td>
<td> Espacio que dejamos en la izquierda ( normalmente en % ) </td>
</tr>
<tr>
<td><strong>transform: translate(x, y)</strong></td>
<td>Transladar a las coordenadas de X e Y</td>
</tr>
<tr>
<td><strong>color</strong></td>
<td>Color de las letras</td>
</tr>
<tr>
<td><strong>text-shadow</strong></td>
<td>Sombreado de texto</td>
</tr>
<tr>
<td><strong>font-weight</strong></td>
<td>Tamaño de la fuente de la letra</td>
</tr>
<tr>
<td><strong>transition-property</strong></td>
<td>Propiedades que van a realizar la transicion que asignemos</td>
</tr>
<tr>
<td><strong>transition-duration</strong></td>
<td>Tiempo que va a durar la transicion en realizarse</td>
</tr>
</table>

```css
.button{
    background-color: red;
    width: 500px;
    height: 100px;
    font-size: 50px;
    text-align: center;
    line-height: 100px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-shadow: 0 3px black;
    font-weight: bold;
    transition-property: all;
    transition-duration: 0.5s;
}
```

<table style="text-align:center">
<tr>
<td><strong>:hover</strong></td>
<td>Se activa cuando nos desplazamos por el elemento con el cursor</td>
</tr>
<tr>
<td><strong>box-shadow</strong></td>
<td>Sombreado de la caja, su contorno y el color del que lo queremos</td>
</tr>
</table>

```css
.button:hover{
    box-shadow: 0px 0px 30px  red;
    width: 700px;
    background-color: red;
    text-shadow: 0 0 5px white;
}
````
