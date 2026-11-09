# 🎵 Sistema Musical — Front-End

Este projeto é uma interface web desenvolvida para um **Sistema de Gestão Musical**. A aplicação permite a navegação entre a gestão de artistas, o registo e organização de obras musicais e a visualização da biblioteca de músicas através de filtros.

---

## 📌 Funcionalidades

- **Autenticação (Login):** Interface de entrada para utilizadores com credenciais de teste para demonstração (`admin` / `123`).
- **Painel Principal (Dashboard):** Menu de navegação em grelha com acesso rápido às principais áreas do sistema.
- **Gestão de Artistas:**
  - Formulário para registo de novos artistas (nome, género musical, país e foto).
  - Tabela de listagem com ações rápidas (editar, eliminar e aceder às músicas do artista).
- **Cadastro de Músicas:**
  - Formulário para vinculação de músicas a artistas cadastrados.
  - Campos para título, álbum, género, link do vídeo no YouTube, imagem de capa e letra da música.
  - Listagem de músicas cadastradas por artista.
- **Biblioteca Musical:**
  - Visualização global de todas as músicas do sistema.
  - Filtros de pesquisa por busca geral (título/álbum/artista), artista e género.
  - Acesso direto para assistir ao vídeo no YouTube.

---

## 📂 Estrutura de Ficheiros

```text
.
├── index.html              # Menu principal (Dashboard)
├── login.html              # Tela de login
├── cadastro_artista.html   # Formulário e listagem de artistas
├── cadastro_musica.html    # Formulário e listagem de músicas
├── listagem_musicas.html   # Biblioteca musical com filtros
└── styles.css              # Estilos globais do sistema
