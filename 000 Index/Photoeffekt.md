---
title: Photoeffekt
class: "[[Wellen]]"
author: Kolja Kahl
tags:
  - "#schule"
created: 2025-09-08
---
### Vakuumphotozelle
![[Inverser Photoeffekt 2025-09-02 12.06.29.excalidraw]]

### Messwerte:

| $\lambda$ (nm) | $U_{max}$ (V) |
| -------------- | ------------- |
| 611            | 0.087         |
| 588            | 0.149         |
| 525            | 0.445         |
| 505            | 0.529         |
| 473            | 0.663         |
```chart
type: line
labels: [611, 588, 525, 505, 472]
series:
  - title: Umax (V)
    data: [0.087, 0.149, 0.445, 0.529, 0.663]
tension: 0
width: 80%
labelColors: false
fill: false
beginAtZero: true
bestFit: false
bestFitTitle: undefined
bestFitNumber: 0
```


![[Graph Photoeffekt.heic]]
Grenzfrequenz

### Interpretation des $f$-$E_{Kin_{max}}$-Diagramms (Photoeffekt)
- erst ab einer bestimmten Frequenz werden Elektronen ausgelöst (Grenzfrequenz $f_{Gr}$)
- einen Teil der eingestrahlten Energie benötigt die Elektronen, um die Austrittsenergie $W_{A}$ zu erreichen
- Die Steigung im Diagramm ist stets $h$!
$$
E = h \cdot f - W_{A}
$$
- Bestimmung des Metalls: abgelesen $W_{A} =  30 \cdot 10^{-20}J = 1.90eV$
- Cäsium (IQB)

## S. 193 Nr. 1
$10^{12} \cdot \frac{hc}{600nm+1 \cdot 10^{-6}s} = 0.33107W$

## S. 193 Nr. 2
$E_{Kin} = h \cdot \frac{c}{460nm}-3.24*10^{-19}J = 1.08J$
$v = \sqrt{ \frac{2 \cdot E_{Kin}}{m} } = \sqrt{ \frac{2 \cdot 1.08J}{9.11 \cdot 10^{-30}Kg} } = 486578 \frac{m}{s}$

# These von Louis de Broglie
$\lambda = \frac{h}{p}$
Jedem Quant lässt sich eine Wellenlänge zuordnen.
Schärfer: Jedes Quant hat Welleneigenschaften, wie Interferenz.
Beispiel: des Elektron
**Berechne die Wellenlänge eines Elektrons; Es wurde mit $U_{B}=150V$ beschleunigt**

$E = q \cdot U = q \cdot 150V = 2.4 \cdot 10^{-17}J$
$v = 7.26 \cdot 10^{6}$
$\lambda = \frac{h}{M \cdot v} = 1.002 \cdot 10^{-10}m$

# Bedingung für Konstruktive Interferenz
![[Darstellung der Bragg-Bedingung.png]]
$\Delta s = n \lambda$
$\Delta s = 2 \sin{\theta}$

1. Ordnung ($n=1$)
$\lambda = 2 \sin{\theta}$

![](https://virtuelle-experimente.de/bilder/elektronenbeugung/Bragg-Reflexionen-fuer-verschiedene-Wellenlaengen.svg)
![](https://virtuelle-experimente.de/bilder/elektronenbeugung/winkel_elektronenbeugung_graphit.svg)
![](https://virtuelle-experimente.de/bilder/elektronenbeugung/Qualitative_Darstellung_Elektronenbeugung.svg)
**Wellenlänge über Beschleunigungspassung ausrechnen:**
$$
\begin{align}
U_{B}&=1.84 &\text{ kV} \\
E&=2.95\cdot 10^{-16} &\text{ J} \\
v&=2.54 \cdot 10^{7} &\text{ m/s}\\
\lambda&=2.86 \cdot 10^{-11} &\text{ m}
\end{align}
$$
**Wellenlänge über Maxima ausrechnen**
$$
\begin{align} \\
L&=125mm \\
r&=22.mm \\
d&=2.13 \cdot 10^{-10}m \\
\frac{r}{L}&=0.176 \\ \\
\theta &= \frac{\tan ^{-1}(0.176)}{2}\\&=4.9909° \\ \\
\lambda &= 2 \cdot d \cdot \sin(5) \\&= 3.71 \cdot 10^{-11}m \\ \\
\end{align}
$$