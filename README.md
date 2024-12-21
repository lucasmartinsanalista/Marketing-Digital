<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clima em Betim</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f9;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .alert {
            background-color: #ffcccb;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .forecast {
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Clima em Betim</h1>

    <div class="current-weather">
        <h2>Condições Atuais</h2>
        <p><strong>Condição:</strong> Nublado</p>
        <p><strong>Temperatura:</strong> 22°C</p>
    </div>

    <div class="alerts">
        <h2>Alertas de Tempo</h2>
        <div class="alert">
            <p><strong>Alerta Laranja de Tempestade:</strong></p>
            <p>Em vigor até 23h59 de 20/12/2024.</p>
            <p>Previsão de chuvas intensas, ventos fortes e queda de granizo.</p>
        </div>
        <div class="alert">
            <p><strong>Alerta Laranja de Chuvas Intensas:</strong></p>
            <p>De 00h01 até 10h00 de 21/12/2024.</p>
            <p>Previsão de chuvas fortes e ventos intensos.</p>
        </div>
        <div class="alert">
            <p><strong>Alerta Amarelo de Chuvas Intensas:</strong></p>
            <p>De 10h00 de 21/12 até 10h00 de 23/12/2024.</p>
            <p>Previsão de chuvas moderadas e ventos moderados.</p>
        </div>
    </div>

    <div class="forecast">
        <h2>Previsão para os Próximos Dias</h2>
        <ul>
            <li>Sexta-feira: Máx 30°C / Mín 20°C - Chuvas e tempestades.</li>
            <li>Sábado: Máx 27°C / Mín 19°C - Chuvas durante o dia.</li>
            <li>Domingo: Máx 25°C / Mín 19°C - Períodos de chuva.</li>
        </ul>
    </div>
</body>
</html>
