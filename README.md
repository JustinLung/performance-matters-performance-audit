# 🚀 Perfomance Audit Portfolio
![Mockup Image](https://github.com/JustinLung/performance-matters-performance-audit/blob/main/docs/mockup-image.png?raw=true)

## 🍕 Content Audit
Op 25 april 2022, heb ik een Content Audit gehouden met behulp van Lighthouse voor mijn portfolio website. Op deze site worden mijn projecten getoond. Voor deze site heb ik een perfomance score van 78 gekregen. 

[🌐 Link](https://justinlung.com/)  
[😺 Repository](https://github.com/JustinLung/Portfolio)

### 🍝 First Contentful Paint (FCP)
**_'Eerste tekenbewerking met content' (FCP) geeft het tijdstip aan waarop de eerste tekst of afbeelding wordt getoond. Tussen de 0-1.8s wordt er een colorcoding van groen aangegeven. Dit betekent dat de FCP erg snel is._**

Als de FCP langzaam is, dan ligt het waarschijnlijk aan de font load time.

Hierbij wordt mijn portfolio site een tijd van 0,9s gegeven. 

### 🥑 Time to Interactive (TTI)
**_'Time to Interactive (TTI)' is de hoeveelheid tijd die nodig is voordat een pagina volledig interactief is. Tussen de 0-3.8s wordt er een colorcoding van groen aangegeven. Dit betekent dat de TTI erg snel is._**

Als de TTI score matig is, probeer dan onnodige Javascript te verminderen. Het optimaliseren van je Javascript is erg belangrijk voor dit punt.

Hierbij wordt mijn portfolio site een tijd van 1,9s gegeven. 

### 🍊 Speed Index
**_Speed Index laat zien hoe snel de content van een pagina zichtbaar is. Tussen de 0-3.4s wordt er een colorcoding van groen aangegeven. Dit betekent dat de Speed Index snel is._**

Als de Speed Index een matige score heeft, kan je deze verbeteren, door ook je TTI te verbeteren. Denk hierbij aan onnodige Javascript te verwijderen of "visible text" in te laden. 

```css
@font-face {
  font-family: 'Pacifico';
  font-style: normal;
  font-weight: 400;
  src: local('Pacifico Regular'), local('Pacifico-Regular'), url(https://fonts.gstatic.com/s/pacifico/v12/FwZY7-Qmy14u9lezJ-6H6MmBp0u-.woff2) format('woff2');
  font-display: swap;
}
```

Hierbij wordt mijn portfolio site een tijd van 1,5s gegeven. Wat heel raar hiervan is, is dat er een colorcoding van oranje wordt getoond. Dit moet eigenlijk een colorcoding van groen zijn, want het zit binnen het bereik van  0-3,4s.

### 🍙 Total Blocking Time (TBT)
**_Som van alle perioden tussen 'Eerste tekenbewerking met content' (FCP) en 'Tijd tot interactief', wanneer de taaklengte langer duurt dan 50 ms, aangegeven in milliseconden. Tussen de 0-200s wordt er een colorcoding van groen aangegeven. Dit betekent dat de TBT snel is._**

Als de TBT een matige score heeft, kan je deze verbeteren, door onnodige Javascript eruit te halen en third party Javascript efficiënter in te laten laden.

Hierbij wordt mijn portfolio site een tijd van 220ms gegeven.

### 🥮 Largest Contentful Paint (LCP)
_Beschrijf de uitslag van de LCP van de test en toon de resultaten. Beschrijf wat kan worden verbeterd als de score minder dan 90 is._

### 🍿 Cumulative Layout Shift (CLS)
_Beschrijf de uitslag van de CLS van de test en toon de resultaten. Beschrijf wat kan worden verbeterd als de score minder dan 90 is._

## 🍫 Bronnen

## 🍦 Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
