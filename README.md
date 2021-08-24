# PaginaWeb1.2
Actualización de la página HTML con  información adicional, listas, hipervinculos e imágenes.
<!DOCTYPE html>
<html>
  
  <head>
      <! –– En esta parte puse el recuadro donde asigne el color blanco de fondo y bordes color purpura de 5px y se pone el nombre blog de monica cherrez en cursivo.––>
      <div style="text-align:center;"> 
    <p style ="background: white; color:purple; font-weight:bold; padding:8px; border:5px solid purple;"><i>BLOG DE MONICA CHERREZ</i></p>
      </div>
    
  </head>

  <body style="background-color:#FFA4F5;"> <! ––En esta linea asigne un color de fondo solido para toda la pagina-->

 <div style="text-align:center;"> <! ––con esta linea encierro todo el texto que quiero que esté alineado al centro-->
 <a>Mi Universidad:</a>
 <a href="https://www.uacam.mx/">Universidad Autonoma de Campeche</a><br>
 <a>Mi Facultad:</a>
 <a href="https://fi.uacam.mx/">Facultad de ingenieria</a><br>
 <a>Mi Instagram:</a>
 <a href="https://www.instagram.com/monicherrez/?hl=es">@monicherrez</a><br>
 <img src="carita.png"
 alt="Carita feliz para todos."
 width="200"
 height="200">  
 </div><! –– y aqui finaliza todo lo que quiero que este centrado-->
</body>
       
      <header>
         
          <! ––Aqui creo mi tabla que tiene dos filas a las cuales le ponemos distinto color,para la primera es morado y para la segunda es blanco-->
        <table style="margin: 0 auto;" width="900" cellspacing="1" cellpadding="3" border="0" bgcolor="#7F0071">
          <tr><! ––comienza fila 1-->
             <td><font color="#FFFFFF" face="arial, verdana, helvetica"> 
          <b>Datos generales</b>
             </font></td>
          </tr><! ––termina fila 1-->
          <tr><! ––comienza fila 2-->
             <td bgcolor="#ffffcc"> <! ––se le asigna color a la fila>
             <font face="arial, verdana, helvetica">
              <ul>
                <li>NOMBRE:Monica Alejandra Cherrez Solis.</li>
                <li>EDAD:21</li>
                <li>NACIONALIDAD: Mexicana.</li>
                <li>DIA DE NACIMIENTO: 31 de Diciembre.</li>
              </ul>
             </font>
             </td>
          </tr><! ––termina fila 2-->
          </table> 
        
          <br>
          
          <table style="margin: 0 auto;" width="900" cellspacing="1" cellpadding="3" border="0" bgcolor="#7F0071">
            <tr>
               <td><font color="#FFFFFF" face="arial, verdana, helvetica">
            <b>Mis intereses</b>
               </font></td>
            </tr>
            <tr>
               <td bgcolor="#ffffcc">
               <font face="arial, verdana, helvetica">
                <ul>
                  <li>Me gusta mucho estar escuchando musica en mi bocinita.</li>
                  <li>Mi autor preferido del momento es Gary Chapman.</li>
                  <li>Me relaja ejercitarme diariamente.</li>
                  <li>Me encanta decorar mis apuntes de clase.</li>
                  <li>De comida me encantan los camarones empanizados.</li>
                </ul>
               </font>
               </td>
            </tr>
            </table>
         </p>
        
          <br>

          <table style="margin: 0 auto;" width="900" cellspacing="1" cellpadding="3" border="0" bgcolor="#7F0071">
            <tr>
               <td><font color="#FFFFFF" face="arial, verdana, helvetica">
            <b>Goals and motivation</b>
               </font></td>
            </tr>
            <tr>
               <td bgcolor="#ffffcc">
               <font face="arial, verdana, helvetica">
                <ul>
                  <li>QUE QUIERO LOGRAR: Quiero lograr ser exitosa haciendo lo que me apasiona.</li>
                  <li>QUE ME DA ENERGIA: Mis papas y mi hermanita.</li>
                  <li>QUE ME DETIENE: A veces la incertidumbre de no saber si podre lograr todo lo que me proponga.</li>
                  <li>QUE ME MANTIENE DESPIERTA EN LAS NOCHES: Estar combinando mis ropas para hacer looks mientras escucho musica.</li>
                </ul>
               </font>
               </td>
            </tr>
            </table>

        <br>

        <table style="margin: 0 auto;" width="900" cellspacing="1" cellpadding="3" border="0" bgcolor="#7F0071">
            <tr>
               <td><font color="#FFFFFF" face="arial, verdana, helvetica">
            <b>A day in the life of...</b>
               </font></td>
            </tr>
            <tr>
               <td bgcolor="#ffffcc">
               <font face="arial, verdana, helvetica">
                <ul>
                    <li>QUE HACE UN DIA EXITOSO: Mi dia es exitoso cuando soy asendosa.</li>
                    <li>PERSONAS Y COSAS CON LAS QUE INTERACTUO: Mis papas, mi hermanita, mi novio, mi celular, mi laptop, mi bocina, etc.</li>
                    <li>QUE ME HACE SENTIR SATISFECHA: Me hace sentir satisfecha tener un dia productivo donde cumplo con todo lo que tengo planeado para un dia.</li>
                    <li>QUE ME FUSTRA: No cumplir con todo lo que tengo planeado para un dia que deberia ser lleno de productividad.</li>
                </ul>
               </font>
               </td>
            </tr>
            </table><br>


     <div style="text-align:center;"> <! ––Alineamos todo nuestro texto al centro de nuestra pagina-->
      <p>
          Elite ------ Atractivo<br />
          <input type="range" min="0" max="95" />
        </p>
        <p>
          Serio ----- Jugueton<br />
          <input type="range" min="0" max="50" />
        </p> 
        <p>
            Convencional ----- Rebelde<br />
            <input type="range" min="0" max="65" />
          </p> 

          <p>
              Amigable ---- Autoritario<br />
              <input type="range" min="0" max="35" />
            </p> 
            <p>
                Madurez y clasico --- Joven e innovador<br />
                <input type="range" min="0" max="40" />
              </p> 

        </p>
      </div>
  </body>

</html>
