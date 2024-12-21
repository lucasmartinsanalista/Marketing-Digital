<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vídeo Responsivo</title>
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #000;
        }

        .video-container {
            position: relative;
            width: 100%;
            max-width: 560px;
            height: 0;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <div class="video-container">
        <iframe 
            src="https://www.youtube.com/embed/HqRD4eW3gc0?controls=0&autoplay=1&mute=1&loop=1&playlist=HqRD4eW3gc0" 
            title="YouTube video player" 
            allow="autoplay; fullscreen"
            allowfullscreen>
        </iframe>
    </div>
</body>
</html>
