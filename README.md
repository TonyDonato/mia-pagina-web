
<!DOCTYPE html>
<html>
<head>
    <title>Benvenuti nella mia pagina web!</title>
    <style>
        body {
            background-color: #87CEFA; /* Sfondo celeste chiaro */
            margin: 0; /* Rimuove i margini di default */
            padding: 0; /* Rimuove il padding di default */
            font-family: Arial, sans-serif;
        }

        /* Titolo lampeggiante a sinistra */
        h1.lampeggiante {
            animation: blink-animation 2s infinite;
            font-size: 2.5em; /* Imposta la dimensione del font */
            text-align: left; /* Allinea il titolo a sinistra */
            margin-left: 20px; /* Distanza dal margine sinistro */
        }

        @keyframes blink-animation {
            0% { color: red; }
            14% { color: orange; }
            28% { color: yellow; }
            42% { color: green; }
            57% { color: blue; }
            71% { color: indigo; }
            85% { color: violet; }
            100% { color: red; }
        }

        /* Centrare l'immagine con una larghezza di 800px e lasciare spazio sopra e sotto */
        img {
            width: 800px; /* Imposta la larghezza dell'immagine a 800px */
            display: block; /* Fa in modo che l'immagine venga visualizzata come blocco */
            margin: 20px 0; /* Aggiunge margine sopra e sotto l'immagine */
            margin-left: auto;
            margin-right: auto; /* Centra l'immagine orizzontalmente */
        }

        /* Testo sotto l'immagine allineato a sinistra */
        .testo-sottotitolo {
            font-size: 1.8em; /* Aumenta la dimensione del testo */
            font-weight: bold;
            text-align: left; /* Allinea il testo a sinistra */
            margin-left: 20px; /* Dà un po' di margine a sinistra */
        }

        /* Link per il download allineato a sinistra */
        a {
            font-size: 1.5em; /* Imposta una dimensione maggiore per il link */
            color: blue;
            text-decoration: none;
            display: block; /* Fa sì che il link occupi una riga intera */
            margin-left: 20px; /* Dà un po' di margine a sinistra per il link */
            margin-top: 10px; /* Dà un po' di margine tra il testo e il link */
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <h1 class="lampeggiante">Benvenuti nella mia pagina web!</h1>

    <!-- Nuova immagine centrata e con larghezza 800px -->
    <img src="immagine4.png" alt="Immagine4" />

    <!-- Testo sotto l'immagine allineato a sinistra -->
    <p class="testo-sottotitolo">Questi sono i programmi da scaricare:</p>

    <!-- Link per il download -->
    <a href="https://mega.nz/fm/h2cBWDiY" download class="download">Download</a>

</body>
</html>


