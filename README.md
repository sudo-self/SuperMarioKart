[SuperMarioKart](https://SuperMarioKart.vercel.app)
<img width="911" alt="Screenshot 2024-05-11 at 8 10 19 PM" src="https://github.com/sudo-self/SuperMarioKart/assets/119916323/9b01145f-1049-473c-8302-4abf360feaa5">

```
        <style>
            body, html {
                margin: 0;
                padding: 0;
            }
        </style>
    </head>
    <body>
        <div style="width:100%;height:100%;max-width:100%">
            <div id="game"></div>
        </div>
        <script>
            EJS_player = "#game";
            EJS_core = "snes";
            EJS_color = "#000000";
            EJS_startOnLoaded = true;
            EJS_pathtodata = "https://cdn.emulatorjs.org/stable/data/";
            EJS_gameUrl = "SuperMarioKart.smc";
        </script>
        <script src="https://cdn.emulatorjs.org/stable/data/loader.js"></script>
