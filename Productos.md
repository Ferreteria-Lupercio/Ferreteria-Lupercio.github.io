---
title: Productos
layout: default
css: /assets/css/productos.css
---

<h1 style="text-align: center; color: #a32626; font-family: 'Alfa Slab One', serif; margin-bottom: 60px; margin-top: 60px;">
  Nuestros Productos
</h1>

<p style="text-align: center; max-width: 700px; margin: 0 auto 50px auto; font-size: 1.2rem; line-height: 1.6;">
  En Ferretería Lupercio contamos con un amplio surtido de productos de alta calidad para satisfacer las necesidades de nuestros clientes, ya sean profesionales, aficionados o particulares.
</p>

<div class="productos-container">

  <div class="categoria">
    <div class="icono">&#128295;</div> <!-- martillo -->
    <h2>Herramientas Manuales</h2>
    <p>Martillos, destornilladores, llaves, alicates, sierras y mucho más.</p>
  </div>

  <div class="categoria">
    <div class="icono">&#9889;</div> <!-- rayo -->
    <h2>Ferretería Eléctrica</h2>
    <p>Taladros, amoladoras, cables, focos y accesorios eléctricos.</p>
  </div>

  <div class="categoria">
    <div class="icono">&#127960;</div> <!-- construcción -->
    <h2>Materiales de Construcción</h2>
    <p>Cemento, arena, varillas, madera y productos para acabados.</p>
  </div>

  <div class="categoria">
    <div class="icono">&#128278;</div> <!-- tornillo -->
    <h2>Tornillería y Fijación</h2>
    <p>Tornillos, clavos, tuercas, arandelas y anclajes.</p>
  </div>

  <div class="categoria">
    <div class="icono">&#128705;</div> <!-- llave inglesa -->
    <h2>Plomería</h2>
    <p>Tuberías, llaves, conexiones y accesorios para agua y gas.</p>
  </div>

</div>

<div class="calidad">
  <h2>Calidad y Garantía</h2>
  <p>
    Todos nuestros productos cuentan con garantía de calidad y respaldo de marcas reconocidas en el mercado para garantizar tu satisfacción y seguridad.
  </p>
</div>

<style>
  .productos-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    max-width: 900px;
    margin: 0 auto 60px auto;
  }

  .categoria {
    background-color: #f9f9f9;
    border: 2px solid #a32626;
    border-radius: 10px;
    width: 260px;
    padding: 20px 25px;
    box-shadow: 3px 3px 8px rgba(0,0,0,0.1);
    text-align: center;
    transition: transform 0.3s ease;
  }

  .categoria:hover {
    transform: scale(1.05);
    box-shadow: 5px 5px 15px rgba(0,0,0,0.2);
  }

  .categoria h2 {
    color: #a32626;
    font-family: 'Alfa Slab One', serif;
    margin: 15px 0 10px 0;
  }

  .categoria p {
    font-size: 1rem;
    line-height: 1.4;
    color: #333;
  }

  .icono {
    font-size: 50px;
    color: #a32626;
  }

  .calidad {
    max-width: 700px;
    margin: 0 auto 80px auto;
    padding: 25px 40px;
    border: 2px solid #a32626;
    border-radius: 10px;
    background-color: #fff4f4;
    text-align: center;
  }

  .calidad h2 {
    font-family: 'Alfa Slab One', serif;
    color: #a32626;
    margin-bottom: 15px;
    font-size: 1.8rem;
  }

  .calidad p {
    font-size: 1.1rem;
    color: #333;
    line-height: 1.6;
  }

  /* Responsive */
  @media (max-width: 768px) {
    .productos-container {
      flex-direction: column;
      align-items: center;
    }

    .categoria {
      width: 90%;
    }

    .calidad {
      width: 90%;
      padding: 20px;
    }
  }
</style>

<h2 style="text-align: center;">Marcas Destacadas</h2>

<div class="marcas-grid">
  <div class="marca">
    <img src="assets/aquaplas.png" alt="Aquaplas logo">
    <div class="marca-texto">
      Tinacos<br>
      Conectores y codos de PVC<br>
      Tapas y válvulas para agua
    </div>
  </div>
  <div class="marca">
    <img src="assets/astrorey.png" alt="Astrorey logo">
    <div class="marca-texto">
      Calentadores Solares
    </div>
  </div>
  <div class="marca">
    <img src="assets/dewalt.png" alt="DeWalt logo">
    <div class="marca-texto">
      Taladros y rotomartillos<br>
      Atornilladores eléctricos<br>
      Baterías y cargadores
    </div>
  </div>

  <div class="marca">
    <img src="assets/fandeli.png" alt="Fandeli logo">
    <div class="marca-texto">
      Lijas en rollo y disco<br>
      Esmeriles abrasivos<br>
      Accesorios de desbaste
    </div>
  </div>
  <div class="marca">
    <img src="assets/phillips.png" alt="Phillips logo">
    <div class="marca-texto">
      Focos LED y ahorradores<br>
      Interruptores y apagadores<br>
      Extensiones eléctricas
    </div>
  </div>
  <div class="marca">
    <img src="assets/makita.png" alt="Makita logo">
    <div class="marca-texto">
      Sierras circulares<br>
      Lijadoras eléctricas<br>
      Baterías de litio
    </div>
  </div>

  <div class="marca">
    <img src="assets/irwin.png" alt="Irwin logo">
    <div class="marca-texto">
      Sargentos y prensas<br>
      Brocas de impacto<br>
      Cúteres y navajas
    </div>
  </div>
  <div class="marca">
    <img src="assets/truper.png" alt="Truper logo">
    <div class="marca-texto">
      Martillos y desarmadores<br>
      Pinzas y llaves<br>
      Cajas de herramientas
    </div>
  </div>
  <div class="marca">
    <img src="assets/urrea.png" alt="Urrea logo">
    <div class="marca-texto">
      Llaves combinadas<br>
      Dado y matraca profesional<br>
      Maletines mecánicos
    </div>
  </div>

  <div class="marca">
    <img src="assets/iusa.png" alt="IUSA logo">
    <div class="marca-texto">
      Accesorios de plomería<br>
      Sanitarios y llaves de agua<br>
      Tubos de cobre y PVC
    </div>
  </div>
  <div class="marca">
    <img src="assets/exito.png" alt="Éxito logo">
    <div class="marca-texto">
      Discos de corte<br>
      Brocas y puntas<br>
      Desarmadores y llaves
    </div>
  </div>
  <div class="marca">
    <img src="assets/anbec.png" alt="Anbec logo">
    <div class="marca-texto">
      Selladores y siliconas<br>
      Adhesivos para construcción<br>
      Espumas expansivas
    </div>
  </div>
</div>

