<html>
<head>
<title>Menu</title>
<style>

.menu{
background-color:#4da7db;
color: blue;
}

.menu ul {
list-style: none;
padding: 10px;
margin: 0;
    }

.menu li {
      display: inline-block;
      margin-right: 10px;
    }

.menu a {
      text-decoration: none;
      color: white;
    }

.menu a:hover {
      color: pink ;
    }

    
 .menu ul ul {
      display: none;
      position: absolute;
      background-color: #4dcddb;
      z-index: 1;
    }

    .menu li:hover ul {
      display: block;
    }
  </style>
</head>
<body>
  <nav class="menu">
    <ul>
      <li><a href="https://elvirapuriel.github.io/DW.github.io/">Inicio</a></li>
      <li>
        <a href="servicios.html">Servicios</a>
        <ul>
          <li><a href="https://elvirapuriel.github.io/DW/">Servicio 1</a></li>
          <li><a href="https://elvirapuriel.github.io/DW/">Servicio 2</a></li>
        </ul>
      </li>
      <li><a href="portafolio.html">Portafolio</a>
<ul>
          <li><a href="https://elvirapuriel.github.io/DW.github.io/Act2Art%C3%ADculoconImagenyTexto">Proyectos</a></li>
          <li><a href="https://elvirapuriel.github.io/DW.github.io/Act3CuatroCajasenContenedor">Actividades</a></li>
        </ul>
</li>
      <li>
<a href="contacto.html">Contacto</a>
<ul>
          <li><a href="https://elvirapuriel.github.io/DW.github.io/Actividad1TarjetadePerfil">Perfil</a></li>
                  </ul>

</li>

    </ul>
  </nav>

  </body>
</html>
