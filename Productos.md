---
title: Productos
layout: default
css: /assets/css/productos.css
---

<h1 style="text-align: center; color: #a32626; font-family: 'Alfa Slab One', serif; margin-bottom: 40px;">
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

<h2 style="text-align: center;">Nuestras Marcas Destacadas</h2>

<div class="marcas-grid">
  <div class="marca">
    <h3>Aquaplas</h3>
    <ul>
      <li>Tubería hidráulica y sanitaria</li>
      <li>Conectores y codos de PVC</li>
      <li>Tapas y válvulas para agua</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Astrorey</h3>
    <ul>
      <li>Láminas galvanizadas</li>
      <li>Canales estructurales</li>
      <li>Accesorios para techado</li>
    </ul>
  </div>

  <div class="marca">
    <h3>DeWalt</h3>
    <ul>
      <li>Taladros y rotomartillos</li>
      <li>Atornilladores eléctricos</li>
      <li>Baterías y cargadores</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Fandeli</h3>
    <ul>
      <li>Lijas en rollo y disco</li>
      <li>Esmeriles abrasivos</li>
      <li>Accesorios de desbaste</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Phillips</h3>
    <ul>
      <li>Focos LED y ahorradores</li>
      <li>Interruptores y apagadores</li>
      <li>Extensiones eléctricas</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Makita</h3>
    <ul>
      <li>Sierras circulares</li>
      <li>Lijadoras eléctricas</li>
      <li>Baterías de litio</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Irwin</h3>
    <ul>
      <li>Sargentos y prensas</li>
      <li>Brocas de impacto</li>
      <li>Cúteres y navajas</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Truper</h3>
    <ul>
      <li>Martillos y desarmadores</li>
      <li>Pinzas y llaves</li>
      <li>Cajas de herramientas</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Urrea</h3>
    <ul>
      <li>Llaves combinadas</li>
      <li>Dado y matraca profesional</li>
      <li>Maletines mecánicos</li>
    </ul>
  </div>

  <div class="marca">
    <h3>IUSA</h3>
    <ul>
      <li>Accesorios de plomería</li>
      <li>Sanitarios y llaves de agua</li>
      <li>Tubos de cobre y PVC</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Éxito</h3>
    <ul>
      <li>Discos de corte</li>
      <li>Brocas y puntas</li>
      <li>Desarmadores y llaves</li>
    </ul>
  </div>

  <div class="marca">
    <h3>Anbec</h3>
    <ul>
      <li>Selladores y siliconas</li>
      <li>Adhesivos para construcción</li>
      <li>Espumas expansivas</li>
    </ul>
  </div>
</div>

