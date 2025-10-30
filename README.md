# 🎬📍 Buscar-CEP-Filme

O **Buscar-CEP-Filme** é um projeto desenvolvido em **JavaScript**, com o objetivo de **consumir APIs externas** para buscar informações de **endereços a partir de CEPs** e **filmes populares ou pesquisados por título**.  
O projeto integra duas APIs distintas, mostrando na prática como trabalhar com **requisições HTTP**, **tratamento de respostas JSON** e **renderização dinâmica no front-end**.

---

## 🎯 Objetivo do Projeto

Este projeto tem dois propósitos principais:

1. 🔎 **Buscar CEP** – Consultar informações de endereço (rua, bairro, cidade e estado) com base em um CEP digitado pelo usuário.  
2. 🎥 **Buscar Filme** – Consultar dados de filmes (título, sinopse, nota e imagem) usando uma API de filmes como a [OMDb API](https://www.omdbapi.com/) ou [The Movie Database (TMDb)](https://www.themoviedb.org/).

---

## ⚙️ Funcionalidades

- 📮 Busca de endereço completo por CEP  
- 🎞️ Pesquisa de filmes por título  
- 🧠 Exibição dinâmica dos resultados na página  
- ⚠️ Tratamento de erros (CEP inválido, filme não encontrado etc.)  
- 💅 Interface simples e responsiva  
- 🔄 Requisições assíncronas usando `fetch()` e `async/await`  

---

## 🧠 Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| **HTML** | Estrutura da aplicação |
| **CSS** | Estilização e layout responsivo |
| **JavaScript (ES6+)** | Lógica principal e consumo das APIs |
| **Fetch API** | Requisições HTTP assíncronas |
| **APIs Externas** | Consulta de CEP e filmes (ViaCEP e OMDb/TMDb) |

---

## 🌐 APIs Utilizadas

### 🏠 ViaCEP
- URL base: `https://viacep.com.br/ws/{CEP}/json/`  
- Retorna dados de endereço com base no CEP informado.

### 🎬 OMDb API (ou TMDb)
- URL base (OMDb): `https://www.omdbapi.com/?t={TITULO}&apikey={SUA_CHAVE}`  
- Retorna título, ano, gênero, sinopse e avaliação do filme.  

> 💡 Você pode obter uma chave gratuita de API no site oficial:  
> 🔗 [https://www.omdbapi.com/apikey.aspx](https://www.omdbapi.com/apikey.aspx)

---

## 🗂️ Estrutura do Projeto

📁 buscar-cep-filme

│

├── 📄 index.html

├── 🎨 style.css

├── ⚙️ script.js

│

├── 📁 assets/

│ └── icons, imagens e logotipos

│

└── 📄 README.md


---

## 💻 Como Executar o Projeto

### 🔹 1. Clonar o repositório
```bash
git clone https://github.com/seu-usuario/buscar-cep-filme.git
cd buscar-cep-filme
```

2. Abrir o projeto no navegador

Basta abrir o arquivo index.html diretamente no navegador.
Não há necessidade de servidor local.

🧩 Exemplo de Uso
🔎 Buscar CEP

Digite um CEP válido (ex: 01001000) e clique em Buscar:
➡️ O app exibe o endereço completo retornado pela API ViaCEP.

🎥 Buscar Filme

Digite o nome de um filme (ex: Inception) e clique em Pesquisar:
➡️ O app exibe o pôster, ano, gênero, nota e sinopse do filme.


🚀 Melhorias Futuras

🧭 Mapa interativo (API do Google Maps) para exibir o endereço

🎨 Modo escuro / claro

🔍 Filtros avançados de filmes (por gênero, nota, ano)

💾 Histórico de buscas armazenado no LocalStorage

⚙️ Migração para React ou Next.js
