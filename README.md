
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BebidasBEVHS24</title>
    <style>
        body {
            
            font-family: Arial, sans-serif;
            background-image: url('https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhl6CqXpofWn_sXvs5zR2Zrm2dy_aWFN3_ks0eixNJSIixZoX1Kb4u8VaxN51AKsCE68l1fb0ILIGu4c289dyl9sdNiu-t1VQsi8uMj9VWRyGODi2j9WC9Ei6qW-gqXRixbxGNLAcMDJcPQ2VuAnrPEeEf8KSricwi5k2rIziBKzT7GxwVFjsrX_iEWbDU/s4096/Picsart_24-11-06_18-11-38-462.pngBJZjJnJHluiPTcozyhdVFKK3FK1DmVQZtH54YGz2Q_FUl-MJSw3d_kU1ztqN2OLUQoVxm9XZc6V0TbyeECNF3s0JIAU_5bVLXnlscQqOyaQV8b5JFNScSDzzVjRiSTn7xw1CY24wkMKXDT9vtilr2KGAl8QAp72GVGBpbXRO3n3jqdMFbMUs9F-tekkvURvWPnr_J3gzz3h-ZSa_wDVXQXiDlaYBl4Rotfu8n8dejv6m_UbLR99sm23LyPB5Sq6g2VR5yl_mo80G_n0Fi_Y9yTf874Ekgfdd3Mm-7v1YZ1DeWYyJ30McTlPLTnFbeOLi1EV3uhejCvzVm8jBPhkbIPoLf7-9GkDiMmkFmjPvs2ufURGu7gCRIPYGvg94e0cxoR_qgGaKUW8qTzvlokdGIuWiiXEKONHS-yiw96GJ9P1PzlIRJj9HJGSv2rarQdZDMIwiGtbDtobbiTJbfV5atOUQmy6TMJrYVgOKsFl6M73nqvJVUBXIQv2_y3IfgVcX-aCIwL_432mAzug4tj3MoRB_nvfwvd16_BHCum1aNPtx80ZACuWoW95Vvi2X5G2LkkYaEcRP7CgN0slGYvcp4mHOW0OVTKLeWETZ-w2zVaJw9KaOfG92a0x-UwevfNV7cVN0eEeAtfVP0wxig_xo0L-4rh1gaBOTQHlCpctjPFfuYhSR5_8URiED60iyi7nlEeOfLNFs-mID74l2_BgSGgVUOa58Gr_B59WWetvOiVSDNfwgCpfpmIOWLEu2rbmyZEHljr6QQCEmYfkjTPRxIsuSrrGScyn_F8l_sVN7yCc7aIJHDGPQ6ha_mWeNwZWUhxtenyxrLONOb-ihx8PkFpFMuhYDld5tNevOs-Eed3av_ingGKnkVO0W0lghfdCxlorvm_vODluAfWT44fwUA2HQS8EzAv17cYxehUg5rm5V-DtJWtKjLjeGLMs88zVv4Uw4rkGxTgCw5WVC9QCpaEY4FBKwJmrTz16QjSCpUoUen-pmOIui---ZEECzo6kKk0CsuO7edZfsbuR-k4glU18KWnn3_mQe32RN_WfT-g8L1AF7g3ce8ofD-cocWQNJJNQkmDrtw_lCbe6DRJbAuubFOng6ZXIxOSI2ceuleugnwJ6E2Q7-IQhEdw7LghtFm-VJgtrWjZERor0TWhezfXkYOTfdLTO5SX1ePenjz6i8rkc1M9sSZBbjU_kzfFbzjIT_iuB7IV3C2XfCBtBKMXJ06iVIsS7L5TP42otEl3x2kA9mcoAQSeaS4YDI1joZr-kU8G26wH4rOpTXM5H9BBsFlclAbv6dbOY5I_-zb7OLdrj13rv0z2hCrzoc8AzQf-vU7R4GWZwinQ=s2048-w1540-h2048-n-k?authuser=0&hl=es-US'); /* Reemplaza con la URL de tu imagen */
            background-size: contain; /* Ajusta la imagen al tamaño de la pantalla sin recortarla */
            background-repeat: no-repeat; /* Evita que se repita */
            background-position: center center; /* Centra la imagen horizontal y verticalmente */
            background-attachment: fixed; /* La imagen queda fija al hacer scroll */
            background-color: #f5f5f5; /* Color de fondo en caso de que la imagen no cubra todo */
            color: #333;
            margin: 0;
            padding: 0;
        }

             
        
        
        .header {
            background-color: #e60012;
            color: #fff;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed; /* Hace que la barra    
            se quede fija */
            width:93%; /* Ocupa el ancho 
            completo */
            top: 0; /* Se coloca en la parte 
            superior de la pantalla */
            z-index: 1000; /* Asegura que esté       
            por encima del contenido */
            
            .header-title {
            font-size: 18px; /* Tamaño de texto  
            para que sea más remarcado */
            font-weight: bold; /* Texto en 
            negrita */
            margin: auto;
            
     }  
        }
        .cart-icon {
            cursor: pointer;
            display: flex;
            align-items: center;
        }
        .cart-icon img {
            width: 27px;
            height: 27px;
            margin-right: 10px;
        }
        .cart-count {
            background-color: #fff;
            color: #e60012;
            border-radius: 50%;
            padding: 3px 6px;
            font-size: 12px;
            font-weight: bold;
            margin-left: 5px;
        }
        .product-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 5px;
            padding: 30px;
            max-width: 800px;
            margin: auto;
            margin-top:35px; /*añadir margen a 
            los productos */
        }
        .product-card {
            background-color: #fff;
            border: 3px solid #ddd;
            border-radius: 8px;
            padding: 5px;
            text-align: left;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
        }
        .product-title {
            font-size: 16px;
            font-weight: bold;
            margin: 0px  5px;
            text-align: center;
        }
        .price {
            font-size: 18px;
            color: #e60012;
            font-weight: bold;
            text-align: center;
        }
        .quantity-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 5px 0;
        }
        .quantity-button {
            background-color: #e60012;
            color: #fff;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 4px;
            margin: 0 5px;
        }
        .quantity-input {
            width: 40px;
            text-align: center;
            font-size: 16px;
            margin: 0 5px;
        }
        .add-button {
            background-color: #e60012;
            color: #fff;
            border: none;
            padding: 10px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }
        .add-button:hover {
            background-color: #cc0010;
        }
        .modal {
            display: none;
            position: fixed;
            top:  0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            justify-content: center;
            align-items: center;
        }
        .modal-content {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            width: 90%;
            max-width: 500px;
            text-align: center;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }
        .modal h3 {
            color: #e60012;
        }
        .close-button, .whatsapp-button {
            background-color: #e60012;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 20px;
        }
        .whatsapp-button {
            background-color: #25D366;
        }
        .cart-item {
    border: 1px solid #ddd; /* Borde del cuadro */
    padding: 10px;          /* Espaciado interno */
    border-radius: 8px;     /* Bordes redondeados */
    margin-bottom: 10px;    /* Espacio entre productos */
    background-color: #f9f9f9; /* Fondo del cuadro */
}
        /* Estilo para el botón de eliminar (X) en el carrito */
        .cart-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
        }

        .cart-item button {
            color: white; /* Cambia el color a rojo */
            border: 50%;
            border-radius:4px;
            background: red;
            cursor: pointer;
            font-size: 18px; /* Aumenta el tamaño del botón si es necesario */
            font-weight: bold;
        }
        <!-- buscador -->
        .header {
    background-color: #e60012;
    color: red;
    padding: 15px 2ppx;
    display: flex;
    justify-content: center; /* Centra todo el contenido dentro del encabezado */
    align-items: center;
    position: fixed; /* Hace que la barra se quede fija */
    width: 90%; /* Ocupa el ancho completo */
    top: 0; /* Se coloca en la parte superior de la pantalla */
    z-index: 1000; /* Asegura que esté por encima del contenido */
}

/* Estilo para la lupa y el campo de búsqueda */
.search-container {
    position: absolute;
    left: 20px;
    top: 17px;
    display: flex;
    align-items: center;
    transition: all 0.3s ease; /* Animación para la transición */
}

.search-icon {
    width: 26px;
    height: 26px;
    cursor: pointer;
}

.search-input {
    display: none; /* Inicialmente oculto */
    width: 200px;
    padding: 5px;
    margin-left: 10px;
    font-size: 16px;
    border-radius: 4px;
    border: none ;
}

.search-input.show {
    display: block; /* Cuando se muestra la caja de búsqueda */
}
<!-- encerrar productos  -->
    
    </style>
</head>
<body>
<div class="header">
    <!-- Contenedor para la lupa y el campo de búsqueda -->
    <div class="search-container">
        <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgM2iPX94jD2rVktPGk80iCdvopTdtI69MFLxoUFRBmigxVuzw1Kwbiga2iqmKmWWdVRQUg6VVcjqcBvtiXNnY7Th_nfiYPmFXvhVEMDsYvPza3XKTcvT1KI_hDgGRokGfftT-_EZtfmuMp3syVC2k3LHe00ACAOnL9tBOxH7-JTQuYJRDQFpuOGSkHh8k/s320/klipartz.com.png" alt="Buscar" class="search-icon" onclick="toggleSearch()">
        <input type="text" id="search-input" class="search-input" placeholder="Buscar productos..." oninput="searchProducts()">
    </div>
    
    <!-- Título de la barra de navegación -->
    <div class="header-title">BebidasBEVHS24</div>
    
    <!-- Icono del carrito -->
    <div class="cart-icon" onclick="toggleModal()">
        <img src="https://cdn-icons-png.freepik.com/512/3393/3393991.png" alt="Carrito de Compras">
        <div class="cart-count" id="cart-count">0</div>
    </div>
</div>
    <!-- colocar productos -->
</div>

<div class="product-container">
    <div class="product-card">
        <img src="https://statics.dinoonline.com.ar/imagenes/large_460x460/3070962_l.jpg" alt="Dr Lemon Vodka 1L">
        <div class="product-title">Dr.Lemon Con Vodka 1L</div>
        <div class="price" data-price="3350">$3.350</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('vodka1l', -1)">-</button>
            <input type="number" id="quantity-vodka1l" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('vodka1l', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Dr. Lemon Con Vodka 1 L', 3350 , 'vodka1l')">Agregar</button>
    
</div>
    <div class="product-card">
        <img src="https://statics.dinoonline.com.ar/imagenes/large_460x460/3070991_l.jpg" alt="Dr Lemon Vodka pomelo ">
        <div class="product-title">Dr.Lemon Vodka Pomelo 1L</div>
        <div class="price" data-price="2100">$2.100</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Dr.Lemon Vodka Pomelo 1L', -1)">-</button>
            <input type="number" id="quantity-Dr.Lemon Vodka Pomelo 1L" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Dr.Lemon Vodka Pomelo 1L', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Dr.Lemon Vodka Pomelo 1L', 2100, 'Dr.Lemon Vodka Pomelo 1L')">Agregar</button>
   </div>
   <!-- Productos del carrito adicionales-->
   <div class="product-card">
        <img src="https://borrachines.com.ar/wp-content/uploads/2023/07/New-Style-1000ml-Mercado-Libre-e1723555073136.png" alt="New Style Vodka 1000ml">
        <div class="product-title">New Style Vodka 1000ml</div>
        <div class="price" data-price="2100">$5.200</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('vodkaPomelo473', -1)">-</button>
            <input type="number" id="quantity-vodkaPomelo473" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('vodkaPomelo473', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('New Style Vodka 1000ml', 5200, 'vodkaPomelo473')">Agregar</button>
   
</div>
    <div class="product-card">
        <img src="https://acdn.mitiendanube.com/stores/002/153/906/products/frizze-evolution-blue-1000ml-a-7b7dd9c3de0f480bc817011156184023-640-0.webp" alt="Espumante Frizze Evolution Blue 1 L">
        <div class="product-title">Espumante Frizze Evolution Blue 1 L</div>
        <div class="price" data-price="2100">$3.200</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('vodkaPomelo473', -1)">-</button>
            <input type="number" id="quantity-vodkaPomelo473" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('vodkaPomelo473', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Espumante Frizze Evolution Blue 1 L', 3200, 'vodkaPomelo473')">Agregar</button>
        
        
   </div>
    <div class="product-card">
        <img src="https://carrefourar.vtexassets.com/arquivos/ids/272447/7792798012633_01.jpg?v=638103580241200000" alt="Sidra Isidra Patagonia Frutada Con Sauco 750 Cc ">
        <div class="product-title">Sidra Isidra Patagonia Frutada Con Sauco 750 Cc</div>
        <div class="price" data-price="7000">$7.000</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Sidra Isidra Patagonia Frutada Con Sauco 750 Cc', -1)">-</button>
            <input type="number" id="quantity-Sidra Isidra Patagonia Frutada Con Sauco 750 Cc" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Sidra Isidra Patagonia Frutada Con Sauco 750 Cc', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Sidra Isidra Patagonia Frutada Con Sauco 750 Cc', 7000, 'Sidra Isidra Patagonia Frutada Con Sauco 750 Cc')">Agregar</button>     
       
 </div>
    <div class="product-card">
        <img src="https://beermarket.com.ar/wp-content/uploads/2023/09/BUDWEISER-LATA-710-ML.png" alt="CERVEZA BUDWEISER 710 ML. ">
        <div class="product-title">CERVEZA BUDWEISER 710 ML.</div>
        <div class="price" data-price="2.400">$2.400</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('CERVEZA BUDWEISER 710 ML.', -1)">-</button>
            <input type="number" id="quantity-CERVEZA BUDWEISER 710 ML." class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('CERVEZA BUDWEISER 710 ML.', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('CERVEZA BUDWEISER 710 ML.', 2400, 'CERVEZA BUDWEISER 710 ML.')">Agregar</button>

</div>
    <div class="product-card">
        <img src="https://d1on8qs0xdu5jz.cloudfront.net/webapp/images/productos/b/0000003000/3008.jpg" alt="Cerveza Quilmes Clásica Botella Retornable 1Lt">
        <div class="product-title">Cerveza Quilmes Clásica Botella Retornable 1L</div>
        <div class="price" data-price="2100">$2.600</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Cerveza Quilmes Clásica Botella Retornable 1L', -1)">-</button>
            <input type="number" id="quantity-Cerveza Quilmes Clásica Botella Retornable 1L" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Cerveza Quilmes Clásica Botella Retornable 1L', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Cerveza Quilmes Clásica Botella Retornable 1L', 2600, 'Cerveza Quilmes Clásica Botella Retornable 1L')">Agregar</button>
   
  </div>
    <div class="product-card">
        <img src="https://www.distribuidoraniki.com.ar/database/articulos/fotos/659/Cerveza%20Andes%20Clasica%201lt%20vidrio%20retornable__1.jpg" alt="Cerveza Andes Clasica Botella retornable 1L">
        <div class="product-title">Cerveza Andes Clasica Botella retornable 1L</div>
        <div class="price" data-price="2.500">$2.500</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Cerveza Andes Clasica Botella retornable 1L', -1)">-</button>
            <input type="number" id="quantity-Cerveza Andes Clasica Botella retornable 1L" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Cerveza Andes Clasica Botella retornable 1L', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Cerveza Andes Clasica Botella retornable 1L', 2500, 'Cerveza Andes Clasica Botella retornable 1L')">Agregar</button>
    
</div>
    <div class="product-card">
        <img src="https://www.lacoopeencasa.coop/media/lcec/publico/articulos/1/3/5/135a6da336f97e29b3935def699e96db" alt="Vino de mesa resero tinto 1L">
        <div class="product-title">Vino de mesa resero tinto tetra brik 1L</div>
        <div class="price" data-price="2100">$1.650</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Vino de mesa resero tinto 1L', -1)">-</button>
            <input type="number" id="quantity-Vino de mesa resero tinto 1L" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Vino de mesa resero tinto 1L', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Vino de mesa resero tinto tetra brik 1L', 1650, 'Vino de mesa resero tinto 1L')">Agregar</button>
   </div>
    <div class="product-card">
        <img src="https://www.lacoopeencasa.coop/media/lcec/publico/articulos/9/d/e/9de315c13a5a931ce43c6faad98d959c" alt="Vino de mesa resero blanco tetra brik 1L">
        <div class="product-title">Vino de mesa resero blanco tetra brik 1L</div>
        <div class="price" data-price="2100">$1.650</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Vino de mesa resero blanco tetra brik 1L', -1)">-</button>
            <input type="number" id="quantity-Vino de mesa resero blanco tetra brik 1L" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Vino de mesa resero blanco tetra brik 1L', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Vino de mesa resero blanco tetra brik 1L', 1650, 'Vino de mesa resero blanco tetra brik 1L')">Agregar</button>
   </div>
    <div class="product-card">
        <img src="https://carrefourar.vtexassets.com/arquivos/ids/308980/7791813111214_E01.jpg?v=638146793841070000" alt="Bebida energizante Rockstar bot 500 cc.">
        <div class="product-title">Bebida energizante Rockstar bot 500 cc</div>
        <div class="price" data-price="2100">$700</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Bebida energizante Rockstar bot 500 cc', -1)">-</button>
            <input type="number" id="quantity-Bebida energizante Rockstar bot 500 cc" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Bebida energizante Rockstar bot 500 cc', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Dr. Lemon Vodka Pomelo 473 Ml', 700, 'Bebida energizante Rockstar bot 500 cc')">Agregar</button>
   </div>
    <div class="product-card">
        <img src="https://blowmax.com.ar/wp-content/uploads/2022/08/Bebida-IsotC3B3nica-GATORADE-Manzana-Botella-500-Cc-600x600.jpg" alt="BEBIDA ISOTONICA GATORADE MANZANA X 500CC">
        <div class="product-title">BEBIDA ISOTONICA GATORADE MANZANA X 500CC</div>
        <div class="price" data-price="2100">$1.050</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('BEBIDA ISOTONICA GATORADE MANZANA X 500CC', -1)">-</button>
            <input type="number" id="quantity-BEBIDA ISOTONICA GATORADE MANZANA X 500CC" class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('BEBIDA ISOTONICA GATORADE MANZANA X 500CC', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('BEBIDA ISOTONICA GATORADE MANZANA X 500CC', 1050, 'BEBIDA ISOTONICA GATORADE MANZANA X 500CC')">Agregar</button>
   </div>
    <div class="product-card">
        <img src="https://ardiaprod.vtexassets.com/arquivos/ids/315103-800-auto?v=638599437045130000&width=800&height=auto&aspect=true" alt="Isotónica Gatorade Cool Blue Botella 750 Ml.">
        <div class="product-title">Isotónica Gatorade Cool Blue Botella 750 Ml.</div>
        <div class="price" data-price="2100">$1.750</div>
        <div class="quantity-container">
            <button class="quantity-button" onclick="changeQuantity('Isotónica Gatorade Cool Blue Botella 750 Ml.', -1)">-</button>
            <input type="number" id="quantity-Isotónica Gatorade Cool Blue Botella 750 Ml." class="quantity-input" value="1" min="1" readonly>
            <button class="quantity-button" onclick="changeQuantity('Isotónica Gatorade Cool Blue Botella 750 Ml.', 1)">+</button>
        </div>
        <button class="add-button" onclick="addToCart('Isotónica Gatorade Cool Blue Botella 750 Ml.', 1750, 'Isotónica Gatorade Cool Blue Botella 750 Ml.')">Agregar</button>     

   
 <!-- carrito de Compras -->  
  </div>

<div class="modal" id="cart-modal">
    <div class="modal-content">
        <h3>Carrito de Compras</h3>
        <div id="cart-list"></div>
        <div class="cart-total">
            <strong>Total: $<span id="total-price">0</span></strong>
            <div style="margin: 10px 0;">
        <label for="payment-method">Método de pago:</label>
        <select id="payment-method" style="width: auto; padding: 5px;">
            <option value="transferencia">Transferencia</option>
            <option value="efectivo">Efectivo</option>
        </select>
    </div>
       
       
       </div>
        <input type="text" id="customer-name" placeholder="Ingresa tu nombre completo" style="width: calc(100% - 40px); padding: 10px; margin: 10px auto;">
        <button class="whatsapp-button" onclick="sendToWhatsApp()">Enviar Pedido por WhatsApp</button>
        <button class="close-button" onclick="toggleModal()">Cerrar</button>
    </div>
<!-- fin de carrito de compra -->

   
</div>

<script>
    let cart = [];
    let totalPrice = 0;

    function addToCart(productName, price, productId) {
        const quantityInput = document.getElementById(`quantity-${productId}`);
        const quantity = parseInt(quantityInput.value);
        
        const existingProduct = cart.find(item => item.name === productName);
        if (existingProduct) {
            existingProduct.quantity += quantity;
        } else {
            cart.push({ name: productName, price: price, quantity: quantity });
        }
        
        totalPrice += price * quantity;
        document.getElementById('cart-count').innerText = cart.length;
        updateCartList();
    }

    function updateCartList() {
        const cartList = document.getElementById('cart-list');
        cartList.innerHTML = '';
        cart.forEach((item, index) => {
            const itemElement = document.createElement('div');
            itemElement.className = 'cart-item';
            itemElement.innerText = `${item.name} (${item.quantity} unidad) - $${item.price * item.quantity} `;
            
            const removeButton = document.createElement('button');
            removeButton.innerText = 'X';
            removeButton.onclick = () =>removeFromCart(index); // Función para eliminar del carrito
            itemElement.appendChild(removeButton); // Añadir el botón al producto en la lista
            cartList.appendChild(itemElement); // Añadir el producto a la lista del carrito
        });
        
        document.getElementById('total-price').innerText = totalPrice; // Actualizar el total
    }

    function removeFromCart(index) {
        totalPrice -= cart[index].price * cart[index].quantity; // Reducir el precio total
        cart.splice(index, 1); // Eliminar el producto del carrito
        document.getElementById('cart-count').innerText = cart.length; // Actualizar el contador
        updateCartList(); // Actualizar la lista del carrito
    }

    function toggleModal() {
        const modal = document.getElementById('cart-modal');
        modal.style.display = modal.style.display === 'flex' ? 'none' : 'flex';
    }

    function sendToWhatsApp() {
    const customerName = document.getElementById('customer-name').value;
    const paymentMethod = document.getElementById('payment-method').value;

    if (!customerName) {
        alert('Por favor, ingresa tu nombre completo.');
        return;
    }

    let message = `*BebidasBEVHS24*\n\n*Nombre del cliente:* ${customerName}\n\n*Productos:*\n`;
    cart.forEach(item => {
        message += `- ${item.name} (${item.quantity} unidad) - *$${item.price * item.quantity}*\n`;
    });
    message += `\n*Total:* $${totalPrice}\n\n`;

    // Añadir mensaje personalizado según el método de pago
    if (paymentMethod === "transferencia") {
        message += `*Método de pago:* Transferencia\n*Alias para transferir:* valcortez. `;
    } else {
        message += `*Método de pago:* Efectivo\n*Instrucciones:* Debes abonar en el local cuando vayas a retirar tu pedido.`;
    } 
    // Agregar el mensaje de agradecimiento
    message += `\n\n¡Muchas gracias por su compra!`;

    const whatsappUrl = `https://wa.me/2645058522?text=${encodeURIComponent(message)}`;
    window.open(whatsappUrl, '_blank');
}

    function changeQuantity(productId, change) {
        const quantityInput = document.getElementById(`quantity-${productId}`);
        let currentQuantity = parseInt(quantityInput.value);
        currentQuantity += change;

        if (currentQuantity < 1) {
            currentQuantity = 1;
        }

        quantityInput.value = currentQuantity;
    }
    <!-- buscador -->
    // Función para alternar la visibilidad de la caja de búsqueda
function toggleSearch() {
    const searchInput = document.getElementById('search-input');
    searchInput.classList.toggle('show'); /* Alterna la visibilidad del campo de búsqueda */
    if (searchInput.classList.contains('show')) {
        searchInput.focus(); // Enfocar el campo de búsqueda cuando se despliega
    }
}

// Función de búsqueda de productos
function searchProducts() {
    const searchQuery = document.getElementById('search-input').value.toLowerCase();

    // Obtener todos los productos
    const products = document.querySelectorAll('.product-card');

    // Filtrar productos basados en el nombre
    products.forEach(product => {
        const productTitle = product.querySelector('.product-title').textContent.toLowerCase();
        
        // Mostrar solo los productos que coinciden con la búsqueda
        if (productTitle.includes(searchQuery)) {
            product.style.display = 'block';  // Mostrar producto
        } else {
            product.style.display = 'none';   // Ocultar producto
        }
    });
}
</script>


</body>
</html>
