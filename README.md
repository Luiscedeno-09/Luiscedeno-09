<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ministerio del Trabajo</title>
    
    <!-- Google Fonts y Material Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

    <style>
        /* Estilo global */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            background-color: #f5f5f5;
        }

        /* Estilo del encabezado */
        .header {
            background-color: #12485b;
            color: white;
            display: flex;
            align-items: center;
            justify-content: flex-start; /* Alineado a la izquierda */
            height: 96px;
            padding-left: 00px; /* Padding a la izquierda */
        }

        .header img {
            max-height: 80%; /* Ajustado a 80% */
            margin-left: 0; /* Asegura que no haya margen a la izquierda */
            margin-right: 0; /* Asegura que no haya margen a la derecha */
            padding: 10px 0; /* Espaciado superior e inferior */
        }

        /* Tarjeta de información */
        .card {
            background-color: #ffffff;
            width: 400px;
            margin: 20px auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .card-header {
            background-color: #eceff1;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 16px;
            font-size: 1.2rem;
            color: #12485b;
        }

        .card-header .material-icons {
            color: #12485b;
            font-size: 24px;
        }

        .info-item {
            display: flex;
            align-items: center;
            padding: 16px;
            border-bottom: 1px solid #e0e0e0;
        }

        .info-item:last-child {
            border-bottom: none;
        }

        .info-item .material-icons {
            font-size: 36px;
            color: #12485b;
            margin-right: 16px;
        }

        .info-item .content {
            display: flex;
            flex-direction: column;
        }

        .info-item .title {
            font-weight: bold;
            color: #333;
        }

        .info-item .subtitle {
            font-size: 14px;
            color: #6c757d;
        }
    </style>
</head>
<body>

    <!-- Encabezado -->
    <header class="header">
        <img src="https://sellados.trabajo.gob.ec/sellado/images/baner.jpg" alt="Ministerio del Trabajo">
    </header>

    <!-- Tarjeta de Información -->
    <div class="card">
        <!-- Encabezado de la tarjeta -->
        <div class="card-header">
            <span>Capacitador Independiente</span>
            <i class="material-icons">info</i>
        </div>

        <!-- Elementos de información -->
        <div class="info-item">
            <i class="material-icons">account_circle</i>
            <div class="content">
                <span class="title">AGUIRRE RODRIGUEZ JULIANA BELEN</span>
                <span class="subtitle">Nombres y Apellidos</span>
            </div>
        </div>

        <div class="info-item">
            <i class="material-icons">school</i>
            <div class="content">
                <span class="title">LIMPIEZA Y DESINFECCION HOSPITALARIA</span>
                <span class="subtitle">Curso</span>
            </div>
        </div>

        <div class="info-item">
            <i class="material-icons">picture_in_picture</i>
            <div class="content">
                <span class="title">0958195091</span>
                <span class="subtitle">Documento de Identidad</span>
            </div>
        </div>

        <div class="info-item">
            <i class="material-icons">timer</i>
            <div class="content">
                <span class="title">40</span>
                <span class="subtitle">Horas de Capacitación</span>
            </div>
        </div>

        <div class="info-item">
            <i class="material-icons">description</i>
            <div class="content">
                <span class="title">RESOLUCIÓN No. MDT-CI-CAL-2022-0255</span>
                <span class="subtitle">Código de Resolución</span>
            </div>
        </div>

        <div class="info-item">
            <i class="material-icons">insert_invitation</i>
            <div class="content">
                <span class="title">11/09/2023 - 15/09/2023</span>
                <span class="subtitle">Fecha Inicio - Fecha Fin</span>
            </div>
        </div>
    </div>

</body>
</html>
