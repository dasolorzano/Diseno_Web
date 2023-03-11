<!DOCTYPE html> 

<html lang="es">
    <h1><center><u>Itacate</u></center></h1>
    <h2><center>Los Burritos que todos aman</center></h2>
    <img src="burrito.png" alt="">
    <img src="">
    <h3>Menu de Burritos</h3>
    <dt><b>Acompañamiento</b></dt>
    <ul>
        <li>Pollo, Cerdo, Res .........................................$50</li>
        <li>Champiñones al chipotle ................................$30</li>
        <li>Rajas con crema ...........................................$30</li>
        <li>Pimiento con cebolla ......................................$30</li>
        <li>Extra de carne ............................................$15</li>
        <li>Extra de vegetales ........................................$10</li>
        <li>Extra de salsas ...........................................$5</li>
    </ul>
    <h3>Especiales</h3>
    <ul>
    <dt><b>Luchador</b>
        <dd><i>Chorrido + pimientos...................$65</i></dd>
    </dt>
    <dt><b>Mas sabor</b>
        <dd><i>Barbacoa + champinones................$65</i></dd>
    </dt>
    </dt>
    <dt><b>Mas carne</b>
        <dd><i>chorizo + barbacoa + pimiento y Cebolla  .................$80</i></dd>
    <dt><b>Clasico</b>
            <dd><i>Pollo + champiñones.................$60</i></dd>
    </ul>
    <dt><i>*El burrito incluye complemento y una salsa</i></dt> 
    </dt>
    
    <br><table border="1" >
        <tr>
            <th colspan="10">Bebidas</th>
        </tr>
        <tr>
            <td rowspan="6">Agua</td>
            <th>Sabor</th>
            <th>Vaso</th>
            <th>Litro</th>
        </tr>
        <tr>
            <td>Fresa</td>
            <td>$20</td>
            <td>$40</td>
        </tr>
        <tr>
            <td>Horchata</td>
            <td>$25</td>
            <td>$45</td>
        </tr>
        <tr>
            <td>Limon</td>
            <td>$15</td>
            <td>$35</td>
        </tr>
        <tr>
            <td>Jamaica</td>
            <td>$18</td>
            <td>$32</td>
        </tr>
        <tr>
            <td>Naranja</td>
            <td>$23</td>
            <td>$35</td>
        </tr>
    
    </table>
    
    
    <h2><center>Ordena Tu Pedido</center></h2>
    <h3><center>Combina hasta tres ingredientes</center></h3>
    <form action="https://formspree.io/f/mayzjaqr" method="POST"><br><br>
     Nombre:<input placeholder=" Nombre    Apellido       " size="40" name="nombre"><br><br>
     Direccion: <input placeholder="Calle No.        Col.     Codigo Postal" name="direccion" size="50"><br><br>
     Telefono: <input value="+52" minlength="12" maxlength="13" name="telefono"><br><br>
     Correo electronico <input email="" name="correo electronico"><br><br>
    
    
        <br><br><b>Orden 1</b><br><br>
        <select >
        <option value="5">Pollo </option>
       <option value="5"> Cerdo</option>
        <option value="5">Res</option>
        <option value="5">Rajas con crema</option>
        <option value="5">Pimiento con cebolla</option>
        <option value="5">Champiñones</option>
        </select>
    Cuantos<input type="number" min="1" max="10">
    
        <input type="radio" value="Cebolla" name="cebolla" >cebolla
        <input type="radio" value="Lechiga" name="Lechuga" >lechuga
        <input type="radio" value="crema" name="crema" >crema 
        <input type="radio" value="arroz" name="arroz" >arroz 
        <input type="radio" value="frijles" name="frijoles" >frijoles
        <input type="radio" value="Rojo" name="salsa roja" >salsa roja 
        <input type="radio" value="Verde" name="salsa verde" >salsa verde 
        <input type="radio" value="diabla" name="salsa diabla" >salsa diabla 
        <input type="radio" value="Guacamole" name="Guacamole" >salsa verde
        <input type="radio" value="Chipotle" name="salsa chipotle" >salsa chipotle  
        <br><b>Extra de:</b><br>
        <select>
            <option value="5"> -ninguno-</option>
            <option value="5">Pollo </option>
            <option value="5"> Cerdo</option>
             <option value="5">Res</option>
             <option value="5">Rajas con crema</option>
             <option value="5">Pimiento con cebolla</option>
             <option value="5">Champiñones</option>
            </select>
        <select>
            <option value="5"> -ninguno-</option>
             <option value="5">Pollo </option>
             <option value="5"> Cerdo</option>
             <option value="5">Res</option>
             <option value="5">Rajas con crema</option>
             <option value="5">Pimiento con cebolla</option>
             <option value="5">Champiñones</option>

        </select>
             
             <input type="radio" value="Cebolla" name="cebolla" >cebolla
             <input type="radio" value="Lechiga" name="Lechuga" >lechuga
             <input type="radio" value="crema" name="crema" >crema 
             <input type="radio" value="arroz" name="arroz" >arroz 
             <input type="radio" value="frijles" name="frijoles" >frijoles
             <input type="radio" value="Rojo" name="salsa roja" >salsa roja 
             <input type="radio" value="Verde" name="salsa verde" >salsa verde 
             <input type="radio" value="diabla" name="salsa diabla" >salsa diabla 
             <input type="radio" value="Guacamole" name="Guacamole" >salsa verde
             <input type="radio" value="Chipotle" name="salsa chipotle" >salsa chipotle  


        </select>
    
        <br><br><b>Orden 2 </b><br><br>
        <select >
        <option value="5">Pollo </option>
       <option value="5"> Cerdo</option>
        <option value="5">Res</option>
        <option value="5">Rajas con crema</option>
        <option value="5">Pimiento con cebolla</option>
        <option value="5">Champiñones</option>
        </select>
    Cuantos<input type="number" min="1" max="100">
    
    <input type="radio" value="Cebolla" name="cebolla" > cebolla
    <input type="radio" value="Lechiga" name="Lechuga" >lechuga
    <input type="radio" value="crema" name="crema" >crema 
    <input type="radio" value="arroz" name="arroz" >arroz 
    <input type="radio" value="frijles" name="frijoles" >frijoles
    <input type="radio" value="Rojo" name="salsa roja" >salsa roja 
    <input type="radio" value="Verde" name="salsa verde" >salsa verde 
    <input type="radio" value="diabla" name="salsa diabla" >salsa diabla 
    <input type="radio" value="Guacamole" name="Guacamole" >salsa verde
    <input type="radio" value="Chipotle" name="salsa chipotle" >salsa chipotle  
    
        <br><br><b>Orden 3</b><br><br>
        <select >
        <option value="5">Pollo </option>
       <option value="5"> Cerdo</option>
        <option value="5">Res</option>
        <option value="5">Rajas con crema</option>
        <option value="5">Pimiento con cebolla</option>
        <option value="5">Champiñones</option>
        </select>
    Cuantos<input type="number" min="1" max="100">
    
        <input type="radio" value="Cebolla" name="cebolla">cebolla
        <input type="radio" value="Lechiga" name="Lechuga">lechuga
        <input type="radio" value="crema" name="crema" >crema 
        <input type="radio" value="arroz" name="arroz" >arroz 
        <input type="radio" value="frijles" name="frijoles" >frijoles
        <input type="radio" value="Rojo" name="salsa roja" >salsa roja 
        <input type="radio" value="Verde" name="salsa verde" >salsa verde 
        <input type="radio" value="diabla" name="salsa diabla" >salsa diabla 
        <input type="radio" value="Guacamole" name="Guacamole" >salsa verde
        <input type="radio" value="Chipotle" name="salsa chipotle" >salsa chipotle  
    
        <br><br><b>Bebidas</b><br><br>
        <select >
        <option value="5">Fresa </option>
       <option value="5"> Limon</option>
        <option value="5">Naranja</option>
        <option value="5">Horchata</option>
        </select>
    Cuantos<input type="number" min="1" max="5">
        <input type="radio" value="al tiempo" name="al tiempo" >al tiempo
    
        
     
        <p><select >
        <option value="5">Fresa </option>
       <option value="5"> Limon</option>
        <option value="5">Naranja</option>
        <option value="5">Horchata</option>
        </select>
    Cuantos<input type="number" min="1" max="5">
        <input type="radio" value="al tiempo" name="al tiempo" >al tiempo </p>
    

    <p><br> <input type="submit" value="Enviar">
    </p>
    <input type="reset" value="Borrar">
    
    
    </form>
    
    </dt>


</html>
