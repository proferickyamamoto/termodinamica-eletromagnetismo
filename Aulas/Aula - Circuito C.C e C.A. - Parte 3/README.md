# Aula – Análise de Circuitos com Indutores em C.C. e C.A.

## 🎓 Disciplina: Termodinâmica, Eletricidade e Magnetismo
## ⏰ Duração: 2 horas

---

## 🎯 Objetivos da Aula
- Compreender o comportamento dos **indutores** em circuitos de **corrente contínua (C.C.)** e **corrente alternada (C.A.)**.
- Analisar a resposta de tensão e corrente ao longo do tempo.
- Aplicar leis de Kirchhoff para circuitos com indutância.
- Calcular reatância indutiva e interpretar a defasagem em C.A.

---

## 🔁 Revisão: O que é um Indutor?
> Um **indutor** é um componente que **resiste à variação da corrente elétrica**, armazenando energia em um **campo magnético**.

📌 Símbolo: uma espiral
📌 Equação fundamental:

\$$V_L = L \cdot \frac{di}{dt}\$$

Onde:
- \$$V_L \$$: tensão no indutor
- \$$L \$$: indutância (em Henry – H)
- \$$\frac{di}{dt} \$$: taxa de variação da corrente

---

## 🔋 Indutores em Corrente Contínua (C.C.)
### Comportamento:
- No instante inicial: o indutor **se opõe à corrente** (atua como **resistência infinita**).
- Após longo tempo: atua como **curto-circuito** (resistência nula).

### Equação diferencial (circuito RL série):

\$$V = L \cdot \frac{di}{dt} + R \cdot i\$$

### Solução para corrente no tempo:

\$$i(t) = \frac{V}{R} \left(1 - e^{-\frac{t}{\tau}}\right)\$$

Onde \$$\tau = \frac{L}{R} \$$ é a constante de tempo (segundos)

### Descarga do indutor:

\$$i(t) = I_0 \cdot e^{-\frac{t}{\tau}}\$$

📌 Energia armazenada:

\$$E = \frac{1}{2} L i^2\$$

---

## ⚡ Indutores em Corrente Alternada (C.A.)
### Comportamento:
- Em C.A., a corrente **oscila** e o indutor **resiste** à sua variação.
- O indutor provoca uma **defasagem de 90º**: a **corrente atrasa** em relação à tensão.

### Reatância indutiva:

\$$X_L = 2 \pi f L\$$
- Unidade: ohm (Ω)
- Depende da frequência (quanto maior \$$f \$$, maior a oposição do indutor).

### Impedância em C.A.:

\$$Z = j X_L = j 2 \pi f L\$$

### Corrente em um circuito puramente indutivo:

\$$i(t) = \frac{V_m}{X_L} \cdot \sin(\omega t - 90^º)\$$

---

## 📊 Comparação entre C.C. e C.A.
| Aspecto                   | C.C.                          | C.A.                                 |
|--------------------------|-------------------------------|--------------------------------------|
| Comportamento inicial    | Impede variação brusca        | Resiste constantemente à variação    |
| Comportamento final      | Curto-circuito (R = 0)         | Reatância proporcional à frequência  |
| Tensão-indutor           | Depende de \( \frac{di}{dt} \) | Depende da frequência \( f \)        |
| Defasagem                | Não há                        | Corrente atrasa 90º                  |

---

## 🧪 Exercício Guiado (C.C.)
**Dado:** R = 100Ω, L = 0,5 H, V = 10 V  
**Perguntas:**
1. Qual a constante de tempo \$$\tau \$$?
2. Qual a corrente após 1s? Após 5s?
3. Qual a energia armazenada no indutor com corrente final?

---

## 🔁 Exercício Guiado (C.A.)
**Dado:** L = 50 mH, f = 60 Hz, V = 120 V (eficaz)

**Perguntas:**
1. Calcule a reatância \$$X_L \$$
2. Calcule a corrente eficaz \$$I \$$
3. Esboce o gráfico de tensão e corrente com defasagem de 90°

---

## 🔧 Atividade Prática
Monte os circuitos RL em simuladores (Falstad ou Tinkercad):
- Aplique C.C. e meça a corrente ao longo do tempo
- Aplique C.A. e meça a defasagem entre tensão e corrente
- Observe o comportamento da corrente na comutação

---

## 📚 Referências
- Halliday & Resnick – Fundamentos de Física Vol. 3, cap. 31 e 33
- Simuladores: Falstad, Tinkercad Circuits, PhET

---

📌 Próxima aula: comportamento do capacitor em C.A. e análise de circuitos RLC!

