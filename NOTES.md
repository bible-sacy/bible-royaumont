```ps
foreach ($i in 1..587) { & 'C:\Program Files\GraphicsMagick-1.3.32-Q8\gm.exe' convert -level 25%,1.0,75% .\pngs\1671_petit_histoire_royaumont\1671_petit_histoire_royaumont-$i.png .\pngs\1671_petit_histoire_royaumont_gm\1671_petit_histoire_royaumont_gm-$i.png }
```
