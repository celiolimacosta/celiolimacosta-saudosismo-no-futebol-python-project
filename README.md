# ⚽ Estamos sendo saudosistas com o futebol?

Este projeto parte de uma pergunta comum entre torcedores que acompanharam o futebol das décadas de 1990 e 2000:  
**será que o futebol daquela época era realmente mais emocionante ou estamos sendo saudosistas?**

Utilizando dados históricos da Copa do Mundo, a análise busca investigar se percepções como mais gols, maior protagonismo individual e partidas mais marcantes encontram respaldo em indicadores mensuráveis ao longo do tempo.

O objetivo não é definir se o futebol é melhor ou pior hoje, mas contextualizar essa percepção com dados, explorando padrões e transformações no jogo ao longo das edições do torneio.

---

## 🧭 Objetivo do Projeto

Investigar, a partir de dados históricos da Copa do Mundo, se a sensação de que o futebol das décadas passadas era mais emocionante encontra suporte em métricas objetivas.

A análise se concentra em três dimensões principais:

- **Ofensividade**: quantidade de gols e evolução ao longo das Copas  
- **Equilíbrio**: proximidade dos placares e partidas decididas por margens mínimas  
- **Protagonismo individual vs coletivo**: concentração de gols em jogadores decisivos

---

## 📁 Estrutura do Projeto
```text
saudosismo-no-futebol-python-project/
├── README.md
├── requirements.txt
├── data/
│   ├── results.csv
│   └── goalscorers.csv
└── notebooks/
    ├── 01_ofensividade_ao_longo_das_copas.ipynb
    ├── 02_equilibrio_das_partidas_ao_longo_das_copas.ipynb
    └── 03_dependencia_de_craques_ao_longo_das_copas.ipynb
```
### Notebooks

- **01_ofensividade_ao_longo_das_copas.ipynb**  
  Gols, média vs mediana e evolução ao longo das Copas

- **02_equilibrio_das_partidas_ao_longo_das_copas**  
  Empates, diferença de gols e jogos decididos por 1 gol

- **03_dependencia_de_craques_ao_longo_das_copas.ipynb**  
  Artilheiros, top 5 e concentração de gols
