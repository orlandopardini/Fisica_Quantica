#   Física Quântica & Estruturas Dissipativas — Simulação Numérica em Python

Este repositório reúne códigos, exemplos e simulações numéricas voltados ao estudo de conceitos fundamentais da **Física Quântica**, **Termodinâmica Irreversível** e **Sistemas Auto-Organizados**, explorando, de forma prática, teorias clássicas e contemporâneas desenvolvidas entre o início do século XX e a segunda metade do século XX.

---

##   Contexto Teórico

### **I - Path Integrals (1948)**

O método de **Integrais de Caminho** foi introduzido por Richard P. Feynman em 1948 como uma formulação alternativa da Mecânica Quântica. Ele reinterpreta a evolução de uma partícula não como uma trajetória única, mas como uma soma sobre todas as trajetórias possíveis, cada uma pesando com uma fase de ação. Essa abordagem se tornou essencial na teoria de campos quânticos e métodos estatísticos de muitos corpos.

**Referência:**  
- Feynman, R. P. (1948). *Space-Time Approach to Non-Relativistic Quantum Mechanics*. Reviews of Modern Physics.

---

### **II - Lei da Conservação da Informação**

A evolução de estados quânticos é **unitária**, preservando informação. Na mecânica estatística clássica, o **Teorema de Liouville** (1838) estabelece a conservação do volume no espaço de fases. Em 1976, Stephen Hawking introduziu o paradoxo da perda de informação em buracos negros, reacendendo a discussão da validade dessa lei em gravidade quântica.

**Referências:**  
- Liouville, J. (1838). *Note sur la théorie de la variation des constantes arbitraires*.
- Hawking, S. W. (1976). *Breakdown of Predictability in Gravitational Collapse*. Physical Review D.

---

### **III - Relações de Onsager (1931)**

Lars Onsager formulou, em 1931, relações de reciprocidade para sistemas próximos do equilíbrio, demonstrando que coeficientes de transporte cruzados (ex: calor induzindo fluxo de massa) são simétricos, desde que haja reversibilidade microscópica. Foi laureado com o Prêmio Nobel de Química em 1968 por esta descoberta.

**Referências:**  
- Onsager, L. (1931). *Reciprocal Relations in Irreversible Processes I & II*. Physical Review.

---

### **IV - Estruturas Dissipativas (Prigogine, 1967–1977)**

Ilya Prigogine avançou o estudo de sistemas longe do equilíbrio, mostrando que fluxo constante de energia pode gerar **padrões auto-organizados**, chamados de **Estruturas Dissipativas**. Recebeu o Prêmio Nobel de Química em 1977 por suas contribuições.

**Referências:**  
- Prigogine, I. (1967). *Introduction to Thermodynamics of Irreversible Processes*.
- Prigogine, I. (1977). *Nobel Lecture*.

---

### **V - Padrões de Turing (1952)**

Alan M. Turing, matemático precursor da computação, propôs em 1952 o conceito de **Instabilidade de Difusão**, prevendo a formação de padrões biológicos por interação de reação química e difusão de substâncias. O modelo **Gray-Scott** é uma generalização popular deste mecanismo.

**Referências:**  
- Turing, A. M. (1952). *The Chemical Basis of Morphogenesis*. Philosophical Transactions of the Royal Society B.

---

##   **Sobre este Repositório**

Este repositório contém um notebook (`codigo.ipynb`) com exemplos numéricos de:

* Simulação de Path Integral Monte Carlo para um Oscilador Harmônico  
* Verificação numérica das Relações de Onsager com fluxos acoplados  
* Simulação de Estrutura Dissipativa com o **Modelo Gray-Scott**, reproduzindo o Padrão de Turing em 2D

Cada bloco é comentado com explicações físicas, equações discretizadas e referências ao fundamento teórico.
