[SuperMarioKart](https://SuperMarioKart.vercel.app)
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
