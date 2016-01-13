# Textjustering

Lantmäteriet Terrängkartan - justering av texter (TJUST)

I vissa av filerna från Lantmäteriet finns det ett fält som heter TJUST.
Detta fältet är till för att placera en text eller symbol kring den aktuella punkten.

Lantmäteriet har definierat hur denna variabel används i sin dokumentation enligt följande:

7 8 9
4 5 6
1 2 3

Problemet som uppstår när man vill justera enligt ovan i QGIS är att där definieras samma sak enligt:

0 1 2
3 4 5
6 7 8 

Exempel:

Om TJUST = 7 (vänstra toppen) i LM's fil så hamnar istället texten centrerat under punkten.
För att lösa detta kan man skriva en enkel funktion för att översätta mellan LM's och QGIS definition
 
![alt tag](./1.png)
![alt tag](https://raw.githubusercontent.com/chaoz/QGIS-LM-Terrain-Styles/master/Preview/2.png)
![alt tag](https://raw.githubusercontent.com/chaoz/QGIS-LM-Terrain-Styles/master/Preview/3.png)
![alt tag](https://raw.githubusercontent.com/chaoz/QGIS-LM-Terrain-Styles/master/Preview/4.png)
![alt tag](https://raw.githubusercontent.com/chaoz/QGIS-LM-Terrain-Styles/master/Preview/5.png)
![alt tag](https://raw.githubusercontent.com/chaoz/QGIS-LM-Terrain-Styles/master/Preview/6.png)
![alt tag](https://raw.githubusercontent.com/chaoz/QGIS-LM-Terrain-Styles/master/Preview/7.png)
![alt tag](https://raw.githubusercontent.com/chaoz/QGIS-LM-Terrain-Styles/master/Preview/8.png)

