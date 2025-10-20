# Mi-pagina
Proyecto

<!DOCTYPE html>
<html lang="es">
<head
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú - La Casa del Charquekan</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #8B4513 0%, #D2691E 100%);
            color: #333;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #FFF8DC;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }

        header {
            background: linear-gradient(135deg, #8B0000 0%, #DC143C 100%);
            color: white;
            text-align: center;
            padding: 40px 20px;
            position: relative;
        }

        header::after {
            content: '🌶️ 🦙 🌶️';
            font-size: 2em;
            display: block;
            margin-top: 10px;
        }

        h1 {
            font-size: 2.5em;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2em;
            font-style: italic;
            opacity: 0.9;
        }

        .menu-section {
            padding: 40px;
            border-bottom: 2px dashed #D2691E;
        }

        .menu-section:last-child {
            border-bottom: none;
        }

        h2 {
            color: #8B0000;
            font-size: 2em;
            margin-bottom: 25px;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 2px;
            position: relative;
            padding-bottom: 15px;
        }

        h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 3px;
            background: #DC143C;
        }

        .menu-item {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 25px;
            padding: 15px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .menu-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
        }

        .item-info {
            flex: 1;
        }

        .item-name {
            font-size: 1.3em;
            font-weight: bold;
            color: #8B0000;
            margin-bottom: 8px;
        }

        .item-description {
            color: #666;
            font-size: 0.95em;
            line-height: 1.5;
            font-style: italic;
        }

        .item-price {
            font-size: 1.5em;
            font-weight: bold;
            color: #DC143C;
            margin-left: 20px;
            white-space: nowrap;
        }

        .special-badge {
            display: inline-block;
            background: #FFD700;
            color: #8B0000;
            padding: 3px 10px;
            border-radius: 15px;
            font-size: 0.8em;
            font-weight: bold;
            margin-left: 10px;
        }

        .whatsapp-section {
            text-align: center;
            background: linear-gradient(135deg, #25D366 0%, #128C7E 100%);
            color: white;
            padding: 40px;
        }

        .whatsapp-section h2 {
            color: white;
        }

        .whatsapp-section h2::after {
            background: white;
        }

        .whatsapp-button {
            display: inline-block;
            background: white;
            color: #25D366;
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-size: 1.3em;
            font-weight: bold;
            box-shadow: 0 5px 20px rgba(0,0,0,0.3);
            transition: all 0.3s ease;
            margin-top: 10px;
        }

        .whatsapp-button:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 30px rgba(0,0,0,0.4);
            background: #f0f0f0;
        }

        .whatsapp-button span:first-child {
            margin-right: 10px;
        }

        footer {
            background: #8B0000;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>La Casa del Charquekan </h1>
            <p class="subtitle">Auténtico sabor andino</p>
        </header>

        <div class="menu-section">
            <h2>Charquekan de Llama</h2>
            
            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Charquekan Personal <span class="special-badge">CLÁSICO</span></div>
                    <div class="item-description">Charque de llama deshilachado, mote, papas, queso frito, huevo y llajua picante</div>
                </div>
                <div class="item-price">Bs. 45</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Charquekan Especial</div>
                    <div class="item-description">Doble porción de charque de llama, plátano frito, arroz, papas, queso, huevo y llajua extra</div>
                </div>
                <div class="item-price">Bs. 58</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Charquekan Familiar</div>
                    <div class="item-description">Porción abundante para 2-3 personas con charque de llama y todos los acompañamientos</div>
                </div>
                <div class="item-price">Bs. 95</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Charquekan Súper Familiar</div>
                    <div class="item-description">Porción generosa para 4-5 personas, ideal para compartir en familia</div>
                </div>
                <div class="item-price">Bs. 150</div>
            </div>
        </div>

        <div class="menu-section">
            <h2>Bebidas</h2>
            
            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Chicha de Maíz</div>
                    <div class="item-description">Bebida tradicional fermentada, dulce y refrescante</div>
                </div>
                <div class="item-price">Bs. 8</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Api Morado</div>
                    <div class="item-description">Bebida caliente de maíz morado con canela y clavo de olor</div>
                </div>
                <div class="item-price">Bs. 7</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Mocochinchi</div>
                    <div class="item-description">Refresco de durazno deshidratado con canela</div>
                </div>
                <div class="item-price">Bs. 8</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Jugo Natural</div>
                    <div class="item-description">Papaya, piña, frutilla, maracuyá o tumbo</div>
                </div>
                <div class="item-price">Bs. 10</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Refresco</div>
                    <div class="item-description">Coca Cola, Sprite o gaseosa nacional</div>
                </div>
                <div class="item-price">Bs. 6</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Cerveza Nacional</div>
                    <div class="item-description">Paceña, Huari o Taquiña</div>
                </div>
                <div class="item-price">Bs. 12</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Agua Mineral</div>
                    <div class="item-description">Con o sin gas</div>
                </div>
                <div class="item-price">Bs. 5</div>
            </div>
        </div>

        <div class="menu-section">
            <h2> Postres</h2>
            
            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Helado de Canela</div>
                    <div class="item-description">Helado artesanal con canela molida</div>
                </div>
                <div class="item-price">Bs. 12</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Buñuelos con Miel</div>
                    <div class="item-description">Buñuelos caseros bañados en miel de caña</div>
                </div>
                <div class="item-price">Bs. 15</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Arroz con Leche</div>
                    <div class="item-description">Postre tradicional con canela y pasas</div>
                </div>
                <div class="item-price">Bs. 10</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Flan de Quinua</div>
                    <div class="item-description">Flan cremoso con quinua y caramelo</div>
                </div>
                <div class="item-price">Bs. 14</div>
            </div>

            <div class="menu-item">
                <div class="item-info">
                    <div class="item-name">Sopaipillas</div>
                    <div class="item-description">Masa frita con miel o azúcar</div>
                </div>
                <div class="item-price">Bs. 8</div>
            </div>
        </div>

        <div class="menu-section whatsapp-section">
            <h2>Haz tu Pedido</h2>
            <p style="font-size: 1.1em; margin-bottom: 25px;">Contáctanos por WhatsApp para ordenar tu Charquekan</p>
            
            <a href="https://wa.me/59162763690?text=Hola!%20Me%20gustaría%20pedir%20Charquekan%20de%20Llama" 
               class="whatsapp-button" 
               target="_blank">
                <span style="font-size: 2em;"></span>
                <span>Ordenar por WhatsApp</span>
            </a>
            
            <p style="margin-top: 20px; font-size: 0.9em; opacity: 0.9;">
                Horario: Lunes a Domingo<br>
                11:00 AM - 10:00 PM
            </p>
        </div>

        <footer>
            <p><strong>Charquekan de Llama Tradicional</strong></p>
            <p style="margin-top: 10px;"> Dirección: Mercado Kantuta #123,Oruro</p>
            <p style="margin-top: 5px;">Teléfono: +591 62763690</p>
            <p style="margin-top: 15px; font-size: 0.85em; opacity: 0.8;">© 2025 Todos los derechos reservados</p>
        </footer>
    </div>
</body>
</html>