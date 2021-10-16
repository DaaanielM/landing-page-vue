<template>
  <header class="header">
    <nav class="menu">
      <label class="logo"
        ><i class="fas fa-pizza-slice iconoxd"></i> Brand
        <span>Pizza</span></label
      >
      <ul class="menu_items">
        <li class="active"><a href="#">Inicio</a></li>
        <li><a href="#menu">Menú</a></li>
        <li><a href="#nosotros">Nosotros</a></li>
        <li><a href="#contacto">Contacto</a></li>
        <li>
          <a id="carrito" href="#carrito"
            ><i class="fas fa-shopping-cart"></i
          ></a>
        </li>
      </ul>

      <span class="btn_menu">
        <i class="fas fa-pizza-slice"></i>
      </span>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>



