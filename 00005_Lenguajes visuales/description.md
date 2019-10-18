Gobstones es un lenguaje visual que utiliza **tableros**.
Usando un programa es posible desplazarse y colocar bolitas de colores en los mismos.

Para desplazarse en el tablero se utiliza el comando `Mover` seguido de una dirección y para colocar bolitas el comando `Poner` seguido de un color.

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 3 3
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        cell 1 1 Rojo 1
        head 1 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>