# Songboooko
En sangbog lavet i node.js


Her er er nogle commands som er nyttige - og notater til projektet.

Først og fremmest bør man altid huske at tilføje node_modules til .gitignore (det fandt jeg ud af lidt sent i det her projekt.)

--- Node.js start-up ---
1. "% npm init" starter node projekt<br>
Herunder skal man give forklaringer på spørgsmål.

2. Tilføj " "type": "module" " til packages.json fil. <br>
Således at man kan import og export i projektet.

3. Opret index.js fil i roden af mappen. <br>
Kommando "% node index.js" kører index.js filen <br>
Genvej CTRL+C stopper/genstarter terminalen.

4. Opsæt lokal Node server. <br>
Kan ses i index.js filen.

5. Installér "Nodemon". <br>
Nodemon er kort for "Node Monitor". <br>
Installeres gennem "% npm i -g nodemon". <br>
Man kan nu fremover skrive "% nodemon index.js" når man vil starte monitorering. Den genstarter node når der sker en ændring i koden.

6. Output. <br>
```
response.writeHead(200, {'Content-Type': 'text/html'});
response.write('Hello World! and another test!');
response.end();
```
Skrives inde i arrowfunction under :
```
"http.createServer((request, response) => {
    [hér]
})"
```

