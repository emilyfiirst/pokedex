# 🧩 Pokedex Web

Uma Pokédex interativa feita com **HTML**, **CSS** e **JavaScript (PokeAPI)**.  
O projeto consome dados da [PokeAPI](https://pokeapi.co/) para listar Pokémons com informações de tipo, nome, número e imagem.

---

## 🧠 Descrição

Este projeto simula uma Pokédex, permitindo visualizar Pokémons de forma paginada.  
Os dados são carregados dinamicamente pela API, e o botão **“Load more..”** permite exibir mais resultados até o limite definido.

---

## 🧩 Estrutura do Projeto

```
📁 pokedex
│
├── index.html              # Estrutura principal da página
│
├── assets/
│   ├── css/
│   │   ├── global.css      # Estilos gerais
│   │   └── pokedex.css     # Estilos específicos da listagem
│   ├── js/
│   │   ├── pokemon-model.js  # Classe Pokémon
│   │   ├── poke-api.js       # Comunicação com a PokeAPI
│   │   └── main.js           # Renderização e lógica principal
│   └── images/
│       └── favicon.ico
│
└── README.md
```

---

## 🚀 Funcionalidades

- 🔍 Lista Pokémons com **nome, número, tipos e imagem**.  
- ⚡ Usa **PokeAPI** para carregar dados reais.  
- 📱 Layout responsivo (1 a 4 colunas conforme a tela).  
- ➕ Botão **“Load more..”** para carregar mais resultados (até 151 Pokémons).  

---

## 🎨 Estilos (CSS)

O layout utiliza **cores temáticas por tipo de Pokémon**, por exemplo:
- 🔥 `fire` → Laranja  
- 🌱 `grass` → Verde  
- 💧 `water` → Azul  
- ⚡ `electric` → Amarelo  

Os cartões são organizados com **CSS Grid**, e o design é totalmente **responsivo**.

---

## ⚙️ Como Executar

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/emilyfiirst/pokedex.git
   ```

2. Abra o arquivo `index.html` em qualquer navegador moderno.

3. Clique em **Load more..** para visualizar mais Pokémons.

---

## 🧩 Tecnologias Utilizadas

- **HTML5**
- **CSS3 (Grid, Responsividade)**
- **JavaScript (ES6)**
- **PokeAPI**

---

## 🧠 Lógica JavaScript

- `pokemon-model.js` → Define a classe `Pokemon` com os atributos principais.  
- `poke-api.js` → Responsável por buscar e converter os dados da API.  
- `main.js` → Controla a renderização e paginação dos Pokémons na interface.  

---

## 🧑‍💻 Autor

Desenvolvido como projeto educacional para prática de **consumo de APIs** e **renderização dinâmica com JavaScript**.
