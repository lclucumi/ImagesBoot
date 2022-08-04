## Primera parte

```mysql
SELECT genre_id mo FROM movies mo 
UNION 
SELECT id gen FROM genres gen;
```

### 5. Dado los siguientes diagramas indique a qué tipo de JOIN corresponde cada uno:

<p align="center">
<table>
  <tr>
    <td> <b> Intersección (A∩B) </b> </td>
    <td> <b> Diferencia (A-B) </b> </td>
  </tr>
  <tr>
    <td><img src="./img/Interseccion.png" width=460 height=260></td>
    <td><img src="./img/Left.png" width=460 height=260></td>
  </tr>
 </table>
 </p>
 
 <p align="center">
<table>
  <tr>
    <td> <b> Diferencia (B-A) </b> </td>
    <td> <b> Unión (AUB) </b> </td>
  </tr>
  <tr>
    <td><img src="./img/Right.png" width=460 height=260></td>
    <td><img src="./img/LeftRight.png" width=460 height=260></td>
  </tr>
 </table>
 </p>
