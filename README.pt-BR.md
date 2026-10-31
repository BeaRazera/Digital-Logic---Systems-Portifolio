**Português** | [ English ](README.md)

# Portfólio de Lógica e Sistemas Digitais

Uma coleção de projetos de circuitos lógicos e engenharia de computação desenvolvidos utilizando o **Simulador de Circuitos Falstad**, focando em contadores sequenciais e decodificadores combinacionais.

![Status](https://img.shields.io/badge/Status-Concluído-success?style=flat-square)
![Category](https://img.shields.io/badge/Category-Eletrônica%20Digital-blue?style=flat-square)

---

## Visão Geral dos Projetos

### 1. Contadores Sequenciais (Falstad)
* **Descrição:** Implementação e simulação de circuitos sequenciais digitais utilizando flip-flops.
* **Principais Funcionalidades:**
  - **Contador Assíncrono (3 a 10):** Construído com quatro flip-flops tipo T para realizar a contagem de 3 a 10 com retorno ao estado inicial.
  - **Contador Síncrono (3 bits):** Sequência personalizada (`7 -> 5 -> 2 -> 0 -> 1 -> 3 -> 4 -> 6 -> 7`) projetada com flip-flops JK, tabelas de excitação e simplificação por Mapas de Karnaugh.
  - **Contador em Anel (Controlador de Semáforo):** Anel de 15 estados operando com um clock de 10Hz ($T = 0,1s$) para gerenciar semáforos de veículos e pedestres (Verde: 0,8s, Amarelo: 0,3s, Vermelho: 0,4s).
* **Simulações:** [Contador Assíncrono](https://www.falstad.com/s.php?s=Xoo5gX) | [Contador Síncrono](https://www.falstad.com/s.php?s=4xMk7I) | [Semáforo em Anel](https://www.falstad.com/s.php?s=WMHPkW)

### 2. Decodificador de Conceitos para Display de 7 Segmentos (Falstad)
* **Descrição:** Circuito lógico combinacional que lê uma entrada binária de 4 bits representando notas acadêmicas (0 a 15) e decodifica em conceitos representados por letras em um display de 7 segmentos.
* **Principais Funcionalidades:**
  - **Mapeamento de Conceitos:** Decodifica entradas para `d` minúsculo (notas 0–3), `E` maiúsculo (4–5), `C` maiúsculo (6–7), `b` minúsculo (8), `A` maiúsculo (9–10) e `I` para entradas inválidas (11–15).
  - **Otimização Booleana:** Tabelas-verdade e expressões minimizadas via Mapas de Karnaugh para os 7 segmentos (`a` até `g`).
  - **Implementação:** Construído com portas NOT, AND e OR em lógica ativa alta.
* **Simulação:** [Circuito Decodificador](https://www.falstad.com/s.py?s=VoYGE5)

---

## Estrutura do Repositório

```text
.
├── README.md               # Documentação em Inglês
└── README.pt-BR.md         # Documentação em Português
