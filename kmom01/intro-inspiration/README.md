# Sammanställning från tillfället 261104, jsux

inspelingen finns här (tyvärr dålig ljudkvalité):
https://www.youtube.com/watch?v=Qns7K_Gc-CU&list=PLVDGHjA5-1qY



## inspiration till layout (kmom01, JSUX)

## 
  - **Inspiration:** hitta siter man gillar och som inspiration.
  - typografi
  - design vad gäller t ex luft, färg, bildspråk
  - layout och struktur.
  - **Analys:** undersök en sajt i DevTools (Ctrl + Shift + C)
  - **Struktur:** wireframes kan man göra för snabba/enkla skisser att komma igång.
  - Prototyp i enkel/semantisk html (header/footer/main/nav osv)
  - **Layout:** flexbox, grid, css-varibler/toekns, färg och typografi 
  - **Finish:** detaljer och sista puts 
  - **börja inte med kod, uppfinn inte hjulet** Titta, plocka isär, bygg enkelt, förfina.
  - förstå och lära sig tekniken, kopiera inte rakt av

## siter för inspiration och trender 
- **Design:**
  - Awwwards: https://www.awwwards.com
  - Godly: https://godly.website
  - Siteinspire: https://www.siteinspire.com
  - Land-book: https://land-book.com
  - Httpster: https://httpster.net
  - Dribbble: https://dribbble.com
  - Behance: https://www.behance.net
  - Mobbin: https://mobbin.com
- **Teknik:**
  - State of CSS: https://stateofcss.com
  - web.dev: https://web.dev
  - MDN CSS ("What's new" finns under MDN Blog/Docs): https://developer.mozilla.org/en-US/docs/Web/CSS
  - css-tricks: https://css-tricks.com
  - Smashing: https://www.smashingmagazine.com
  - Codrops: https://tympanus.net/codrops/
- **Kompatibilitet:**
  - Can I use: https://caniuse.com
  - Baseline: https://web.dev/baseline
- **Principer:**
  - Nielsen Norman Group: https://www.nngroup.com
  - *Refactoring UI*: https://www.refactoringui.com
  - Kursboken *Designing Interfaces*  https://www.oreilly.com/library/view/designing-interfaces-3rd/9781492051954/
  - Vi nämnde också "Don't make me think" som exempel på litteratur.

## DevTools
- Inspect (Ctrl+Shift+C):strukturen, semantiska element osv.
- Styles/Computed: egenskaper och se vad de gör.
- Layout: flex- och grid-overlay.
- Box model: margin, padding, border, storlek.
- Övrigt typografi och färg: font-family, storlekar, färgväljar och t ex css-variabler i `:root`.
- Responsive mode: dra i bredden.
- Color picker och pipett: man kan klicka på "färgrutan" bredvid ett färgvärde i Styles-fliken. 
Shift+klick växlar hex/rgb. 
- CSS Overview: Ctrl+Shift+P, klicka *Capture overview*. Visar färgpalett, typsnitt , media queries/brytpunkter, eventuella issues (kontrast) och 'unused' css. 
Fungerar inte i alla webbläsare (ännu)
- **Vi tittade på ett antal siter i devtools:** 
- https://bandcamp.com
- https://vinylmeplease.com
- https://www.bengans.se
- Vi kikade även i Network-fliken för att se varje sites "vikt" samt filer som laddas/hämtas (se "knapparna" Doc, Fetch etc)

**Wireframe**
- Wireframe på papper
-  Excalidraw (https://excalidraw.com) 
- [Figma](https://www.figma.com).
- https://wireframe.cc
- gör ett html-skelett utifrån wireframe.


# Gruppövning: analysera en shop


Anteckna/skriv ner vad ni kommer fram till enligt följande

**Analyswera**
- Väljer en webbshop (gärna en möjlig utgångspunkt/inspiration för kursen).
- Leta fram och ta reda på:
  - Vilka typsnitt används? (rubriker, t ex för H1-H3, brödtext).
  - Hur ser sitens boxmodell ut? (margin, padding, border på ett par element)
  - Vilken eller vilka layouts används? (flex/grid, försöka hitta var och varför)
  - Vilket eller vilka färgscheman hittar ni (exempelvis 3-5 huvudfärger)
- Skriv ner *hur* ni kom fram till det av vad ni använde för att komma hitta detta.
Vid återsamlingen: visa och berätta hur ni gjorde och vad ni kom fram till

**Bygga en 'mall'**
- Skissa en enkel wireframe (kanske på papper, Figma (om man har det) eller kanske Excalidraw) för er shopens förstasida.
- Beskriv och berätta hur ni tänker er typsnitt, boxmodell (struktur/layout), färgscheman.
- Gör en enkel skiss i html/css utifrån wireframen: header, hero, main, footer, gärna med färger och typsnitt som CSS-variabler. 
Utgå från `exempel/04-struktur`.
Vid återsamlingen:
- visa er skiss och berätta hur ni hittade/kom fram till typsnitt, boxmodell, layout och färger.
- Visa wireframen och mallen, och berätta vad ni valde bort eller förenklade.
- Koppla till kursen: det här är samma arbetssätt som uppgiften "Typsnitt och färg" (Urval, Metod, Resultat, Analys).
