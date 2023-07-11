Importe Speaker de la bibliothèque picozero puis définis les broches pour plusieurs buzzers, utilise le code suivant :

--- code ---
---
language: python
filename: 
line_numbers: false
line_number_start: 1
line_highlights: 
---
from picozero import Speaker

hautparleur_1 = Speaker(5)
hautparleur_2 = Speaker(10)
--- /code ---

**Astuce**: Tu voudrais peut-être utiliser des noms de variables spécifiques à ce que le haut-parleur doit faire. Par exemple, `drum_beat`.
