<template>
  <head>
      <!-- Required meta tags -->
    

  </head>
  <body>
  <div>
    <header>
      <nav>
          <ul class="nav justify-content-center">
            <li><a href="#">Pizza</a></li>
            <li><a href="#">Bebidas</a></li>
            <li><a href="#">Hamburguesas</a></li>
            <li><a href="#">Tacos</a></li>
          </ul>
        </nav>
    </header>
  </div>
  <hr>
  <div>
    <h1>COMIDA RAPIDA</h1>
    
  </div>
  <div>
    
      <card url="https://img.freepik.com/foto-gratis/pizza-hawaiana_1203-2455.jpg?size=626&ext=jpg&ga=GA1.2.1370031169.1661046267" nombre="Pizza hawaiana" /> 
    
    
    
    <card url="https://assets.stickpng.com/images/580b57fcd9996e24bc43c1b7.png" nombre="Hot Dogs" />
    <card url="https://assets.stickpng.com/images/585abfc54f6ae202fedf2935.png" nombre="Papas" />
    <Card url="https://img.freepik.com/fotos-premium/empanadas-espanolas-tipicas-blanco_123827-9710.jpg?w=826" nombre="Empanada"/>
    <card url="https://img.freepik.com/vector-gratis/dibujado-mano-ilustracion-michelada-fresca_23-2149205755.jpg?size=338&ext=jpg&ga=GA1.2.1370031169.1661046267" nombre="Bebidas" />
    <card url="https://i.pinimg.com/originals/ef/4a/4a/ef4a4a551b83ee26dbfe2bafe3e34699.png" nombre="Hamburguesas" />
    <card url="https://img.freepik.com/vector-gratis/acuarela-deliciosa-ilustracion-pozole_23-2149189983.jpg?w=740&t=st=1663642195~exp=1663642795~hmac=dc2f7801238bde0bb3c4345abf8a27f58d4167640d75fdf6b1d4eabdc91e6eba" nombre="Pozole" />
  </div>
  <div><p>Citlally Itzel Carrera Sanchez 4°A</p></div>
</body>
</template>

<style>
  nav{
 

}

nav ul {
  list-style: none;
  overflow: hidden; /* Limpiamos errores de float */
}

nav ul li {
  float: left;
  font-family: Arial, sans-serif;
  font-size: 16px;
}

nav ul li a {
  display: block; /* Convertimos los elementos a en elementos bloque para manipular el padding */
  padding: 20px;
  color: black;
  text-decoration: none;
}


h1{
  text-align: center;
}
body{
  background-color: #3382FF;
}

</style>

<script>
  import Card from "./components/Card.vue"
  
  export default {
    components:{
      Card,
    },
  };
</script>