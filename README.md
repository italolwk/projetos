
# 🌱 EcoHealth

> Tecnologia aplicada à saúde pública e conscientização ambiental.

O **EcoHealth** é uma plataforma web desenvolvida com o objetivo de aproximar a tecnologia da saúde pública e da conscientização ambiental.

O sistema permite que usuários registrem problemas ambientais, indiquem sua localização através de um mapa interativo e contribuam para a identificação de situações que possam representar riscos à saúde e ao meio ambiente.

---

## 🎯 Objetivo

O principal objetivo do EcoHealth é incentivar a participação da população na identificação e conscientização sobre problemas ambientais.

A plataforma busca utilizar a tecnologia como ferramenta de apoio para:

- 🌱 Conscientização ambiental
- 🏥 Promoção da saúde pública
- 🦟 Prevenção de doenças
- 🗺️ Identificação de áreas de risco
- 🚨 Registro de denúncias ambientais
- 📚 Educação ambiental
- 👥 Participação da comunidade

---

## 🚀 Funcionalidades

### 🔐 Sistema de autenticação

- Cadastro de usuários
- Login
- Logout
- Proteção das páginas internas
- Armazenamento das informações de acesso

### 🗺️ Mapa interativo

O sistema utiliza um mapa para visualizar os locais das denúncias.

É possível:

- Pesquisar endereços
- Selecionar locais diretamente no mapa
- Utilizar a localização atual
- Visualizar denúncias através de marcadores
- Visualizar concentração de denúncias através de Heatmap

### 🚨 Registro de denúncias

O usuário pode registrar:

- 📍 Local
- 📝 Descrição do problema
- 📸 Imagem
- 🌎 Coordenadas geográficas

As denúncias ficam disponíveis para visualização no mapa.

### 📊 Dashboard

O sistema apresenta estatísticas das denúncias através de:

- Total de denúncias
- Problemas relacionados à água
- Problemas relacionados à poluição do ar
- Resíduos e lixo
- Queimadas

Também existe um gráfico para facilitar a visualização dos dados.

### 🌍 Problemas ambientais

A plataforma apresenta informações educativas sobre problemas como:

- 🦟 Água parada
- 🚱 Água contaminada
- 🗑️ Lixo irregular
- 💨 Poluição do ar
- 🔥 Queimadas
- 🏭 Poluição industrial

### 👥 Agentes de Combate às Endemias

A plataforma apresenta informações sobre as funções dos agentes, incluindo:

- Visitas domiciliares
- Controle de vetores
- Educação da população
- Monitoramento
- Ações preventivas

### 🌱 Conscientização

Área dedicada à conscientização da população sobre:

- Preservação ambiental
- Prevenção de doenças
- Participação social
- Saúde pública
- Sustentabilidade

### 🌙 Modo escuro

O usuário pode alternar entre:

- ☀️ Modo claro
- 🌙 Modo escuro

A preferência é mantida no navegador.

### 🌎 Sistema de idiomas

O projeto possui suporte para alteração do idioma da interface, permitindo adaptar os conteúdos do sistema para diferentes idiomas.

### 📱 Interface responsiva

O sistema foi desenvolvido para funcionar em diferentes tamanhos de tela:

- 💻 Computadores
- 📱 Smartphones
- 📲 Tablets

---

## 🛠️ Tecnologias utilizadas

### Front-end

- HTML5
- CSS3
- JavaScript

### Bibliotecas e APIs

- Leaflet.js
- Leaflet Heatmap
- Chart.js
- OpenStreetMap
- Nominatim API

### Armazenamento

- LocalStorage
- Firebase / Firestore

---

## 📂 Estrutura do projeto

```text
EcoHealth/
│
├── index.html
├── cadastro.html
├── home.html
├── sobre.html
├── problemas.html
├── politica.html
├── comunidade.html
├── contato.html
│
├── style.css
├── script.js
├── firebase.js
│
├── logo.png
├── favicon.png
│
└── README.md
