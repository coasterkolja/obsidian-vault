---
title: Gerücht auf einer Party
class: "[[Wachstum]]"
author: Kolja Kahl
tags:
  - "#schule"
created: 2025-05-21
---
## a)
Das Gerücht wird anfangs von wenigen Personen verbreitet, also verbreitet es sich zunächst **langsam**.  
Sobald mehr Menschen es kennen, verbreitet es sich **schneller**, da mehr Personen es weitererzählen.  
Aber je mehr Leute es wissen, desto **langsamer** wird das Wachstum wieder, weil es **weniger neue Personen gibt**, die es noch nicht kennen.

## b)
Die Aussage ist **richtig**.
- Anfangs ist das Wachstum **exponentiell**, da jede Person das Gerücht an mehrere weitergeben kann (z. B. 2 → 4 → 8 usw.).
- Sobald viele Leute das Gerücht kennen, verlangsamt sich das Wachstum. Es wird **vom "begrenzten" Wachstum abgebremst**, da nur noch wenige Unwissende übrig sind.

## c)
$f′(x) = 0,00025 * f(x) * (800 – f(x))$
→ logistische Differentialgleichung
→ Anfangs wächst f(x) exponentiell, wird aber durch `(800 – f(x))` gebremst

## d)

Gegeben:

$f(x)=8001+399⋅e−0,2xf(x) = \frac{800}{1 + 399 \cdot e^{-0,2x}}f(x)=1+399⋅e−0,2x800​$

#### **i. Prüfung: erfüllt f(x) die DGL aus c)?**

DGL:

$f′(x)=0,00025⋅f(x)⋅(800−f(x))f'(x) = 0{,}00025 \cdot f(x) \cdot (800 - f(x))f′(x)=0,00025⋅f(x)⋅(800−f(x))$

**Ableitung von f(x):**

Setze:

$f(x)=8001+399e−0,2x=800g(x)f(x) = \frac{800}{1 + 399 e^{-0{,}2x}} = \frac{800}{g(x)}f(x)=1+399e−0,2x800​=g(x)800​$

Dann ist:

$f′(x)=−800⋅g′(x)(g(x))2f'(x) = -800 \cdot \frac{g'(x)}{(g(x))^2}f′(x)=−800⋅(g(x))2g′(x)​$

Ableitung von $g(x)=1+399e−0,2xg(x) = 1 + 399 e^{-0{,}2x}g(x)=1+399e−0,2x$:

$g′(x)=−399⋅(−0,2)⋅e−0,2x=79,8⋅e−0,2xg'(x) = -399 \cdot (-0{,}2) \cdot e^{-0{,}2x} = 79{,}8 \cdot e^{-0{,}2x}g′(x)=−399⋅(−0,2)⋅e−0,2x=79,8⋅e−0,2x$

Daher:

$f′(x)=−800⋅79,8⋅e−0,2x(1+399e−0,2x)2f'(x) = -800 \cdot \frac{79{,}8 \cdot e^{-0{,}2x}}{(1 + 399 e^{-0{,}2x})^2}f′(x)=−800⋅(1+399e−0,2x)279,8⋅e−0,2x​$

#### **ii. Anfangswert prüfen**

Setze x=0x = 0x=0 ein:

f(0)=8001+399⋅e0=8001+399=800400=2f(0) = \frac{800}{1 + 399 \cdot e^0} = \frac{800}{1 + 399} = \frac{800}{400} = 2f(0)=1+399⋅e0800​=1+399800​=400800​=2

Also: **Startwert ist 2 Personen** → passt!

Nach 8 Minuten:

f(8)=8001+399e−0,2⋅8≈8001+399⋅e−1,6≈8001+399⋅0,2019≈8001+80,5≈80081,5≈9,8f(8) = \frac{800}{1 + 399 e^{-0{,}2 \cdot 8}} \approx \frac{800}{1 + 399 \cdot e^{-1{,}6}} \approx \frac{800}{1 + 399 \cdot 0{,}2019} \approx \frac{800}{1 + 80{,}5} \approx \frac{800}{81{,}5} \approx 9{,}8f(8)=1+399e−0,2⋅8800​≈1+399⋅e−1,6800​≈1+399⋅0,2019800​≈1+80,5800​≈81,5800​≈9,8

➡️ **Nach 8 Minuten ≈ 10 Personen** kennen das Gerücht ✔ passt!

#### **iii. Wann kennen 400 Personen das Gerücht?**

Setze f(x)=400f(x) = 400f(x)=400:

400=8001+399e−0,2x⇒1+399e−0,2x=2⇒399e−0,2x=1400 = \frac{800}{1 + 399 e^{-0{,}2x}} \Rightarrow 1 + 399 e^{-0{,}2x} = 2 \Rightarrow 399 e^{-0{,}2x} = 1400=1+399e−0,2x800​⇒1+399e−0,2x=2⇒399e−0,2x=1 e−0,2x=1399⇒−0,2x=ln⁡(1399)⇒x=−ln⁡(1399)0,2=ln⁡(399)0,2≈5,990,2≈29,95e^{-0{,}2x} = \frac{1}{399} \Rightarrow -0{,}2x = \ln\left(\frac{1}{399}\right) \Rightarrow x = \frac{-\ln\left(\frac{1}{399}\right)}{0{,}2} = \frac{\ln(399)}{0{,}2} \approx \frac{5{,}99}{0{,}2} \approx 29{,}95e−0,2x=3991​⇒−0,2x=ln(3991​)⇒x=0,2−ln(3991​)​=0,2ln(399)​≈0,25,99​≈29,95

✅ **Nach ca. 30 Minuten** kennen **400 Personen** das Gerücht.

#### **iv. Wann wissen _alle_ (≈800) Bescheid?**

Grenzwert:

lim⁡x→∞f(x)=8001+399e−0,2x=800\lim_{x \to \infty} f(x) = \frac{800}{1 + 399 e^{-0{,}2x}} = 800x→∞lim​f(x)=1+399e−0,2x800​=800

Also **niemals ganz genau 800**, aber **praktisch alle** kennen es, wenn f(x)>799f(x) > 799f(x)>799

Schätzen:

f(x)>799⇒8001+399e−0,2x>799⇒1+399e−0,2x<800799≈1,00125⇒399e−0,2x<0,00125⇒e−0,2x<0,00125399⇒−0,2x<ln⁡(0,00125399)⇒x>−ln⁡(0,00125399)0,2f(x) > 799 \Rightarrow \frac{800}{1 + 399 e^{-0{,}2x}} > 799 \Rightarrow 1 + 399 e^{-0{,}2x} < \frac{800}{799} \approx 1{,}00125 \Rightarrow 399 e^{-0{,}2x} < 0{,}00125 \Rightarrow e^{-0{,}2x} < \frac{0{,}00125}{399} \Rightarrow -0{,}2x < \ln\left(\frac{0{,}00125}{399}\right) \Rightarrow x > \frac{-\ln\left(\frac{0{,}00125}{399}\right)}{0{,}2}f(x)>799⇒1+399e−0,2x800​>799⇒1+399e−0,2x<799800​≈1,00125⇒399e−0,2x<0,00125⇒e−0,2x<3990,00125​⇒−0,2x<ln(3990,00125​)⇒x>0,2−ln(3990,00125​)​ ln⁡(0,00125/399)≈ln⁡(3,13⋅10−6)≈−12,67⇒x>12,670,2≈63,3\ln(0{,}00125/399) ≈ \ln(3{,}13 \cdot 10^{-6}) ≈ -12{,}67 \Rightarrow x > \frac{12{,}67}{0{,}2} ≈ 63{,}3ln(0,00125/399)≈ln(3,13⋅10−6)≈−12,67⇒x>0,212,67​≈63,3

✅ **Nach ca. 63 Minuten** kennt **praktisch jede Person** das Gerücht.