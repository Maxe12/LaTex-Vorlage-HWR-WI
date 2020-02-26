# LaTex-Vorlage-HWR-WI

LaTex Vorlage für PTB/Studienarbeit/BT an der HWR Berlin Duales Studium Wirtschaftsinformatik

Zum Benutzen der Vorlage: 
1. Repository clonen oder downloaden
2. Beispielkapitel (Einleitung, Hauptteil, Schluss) löschen (und deren input tag in der main.tex)
3. Losschreiben

Optionale einstellungen für das Dokument:
1. Möchte man den Seitenumbruch bei neuen Kapiteln verhindern muss eine Group um die eingefügten Kapitel erstellt werden, 
  für die man keine automatischen Umbrüche möchte. Dies kann dann wie folgt aussehen:  
    
    \begingroup 
    
    \let\cleardoublepage\relax

    \input{tex/01_einleitung.tex}

    .....
 
    \input{tex/05_fazit.tex}

    \endgroup

