# 🎵 Spotify — Plataforma de Streaming de Áudio

## 📌 Descrição Geral
O *Spotify* é uma plataforma global de streaming de áudio que oferece acesso instantâneo a um vasto catálogo de músicas, podcasts e conteúdos em áudio. Disponível para múltiplos dispositivos e sistemas operacionais (dispositivos móveis, computadores, tablets e smart TVs), o aplicativo combina entrega contínua via internet com algoritmos avançados de personalização, permitindo que cada usuário adapte sua experiência aos seus gostos e rotinas.

---

## 🎯 Público-Alvo
O Spotify atende a duas vertentes principais de usuários:

* *Ouvintes & Consumidores de Conteúdo:* Pessoas que buscam praticidade e mobilidade para ouvir áudio em alta qualidade. O perfil abrange usuários que desejam:
  * Localizar e reproduzir áudio com rapidez e facilidade;
  * Descobrir novos artistas, tendências e episódios através de recomendações inteligentes;
  * Criar, organizar e compartilhar playlists personalizadas com a comunidade;
  * Sincronizar e acessar seus conteúdos favoritos offline em múltiplos dispositivos.

* *Artistas, Podcasters & Criadores:* Músicos e produtores que utilizam a plataforma como canal oficial de distribuição, análise de métricas, divulgação de lançamentos e engajamento direto com seu público.

---

## ⚙️ Principais Funcionalidades
- *Streaming de Áudio em Alta Definição:* Execução fluida de áudio online com suporte à reprodução offline;
- *Sistemas de Curadoria e Recomendação:* Algoritmos preditivos para geração de mixes diários e descoberta semanal;
- *Gestão de Coleção:* Criação, edição e compartilhamento de playlists;
- *Integração de Mídia e Exibição de Letras:* Exibição sincronizada de letras de músicas durante a reprodução;
- *Retrospectiva Anual (*Spotify Wrapped):** Compilação de estatísticas e hábitos de escuta interativos ao final de cada ano.

## 🛠️ Tecnologias Utilizadas

O ecossistema do Spotify é construído sobre uma arquitetura distribuída e escalável para suportar milhões de usuários simultâneos.

### 📱 Client-Side (Aplicativos e Front-End)
- **Mobile (Android/iOS):** C++ (para o core de áudio compartilhado), Java/Kotlin (Android) e Swift/Objective-C (iOS).
- **Desktop & Web Player:** TypeScript, React e Electron (para a aplicação desktop).
- **Badges:**
  ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
  ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
  ![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

---

### ⚙️ Back-End e Arquitetura de Microserviços
- **Linguagens do Servidor:** Java e Python (usados no processamento e lógica dos microserviços), C++ (servidores de streaming de áudio de alta performance).
- **Processamento de Dados & IA:** Python e Scala para os algoritmos de recomendação e Machine Learning (ex: Descobertas da Semana).
- **Badges:**
  ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)

---

### ☁️ Infraestrutura e Banco de Dados
- **Nuvem:** Google Cloud Platform (GCP).
- **Bancos de Dados:** PostgreSQL (dados relacionais), Cassandra (armazenamento de dados em larga escala) e Redis (caching de alta velocidade).
- **Mensageria & Stream:** Apache Kafka (para streaming de dados em tempo real) e Docker/Kubernetes para orquestração.
- **Badges:**
  ![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
  ![Cassandra](https://img.shields.io/badge/Cassandra-100000?style=for-the-badge&logo=apachecassandra&logoColor=white)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 🎨 Design & UI/UX
- **Ferramentas de Design:** Figma (design de interface e prototipagem do Design System GLUE do Spotify).
- **Badges:**
  ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## 💻 Requisitos do Sistema e Compatibilidade

### 1. Dispositivos e Plataformas
* *Dispositivos Móveis:* Aplicativos dedicados para iOS e Android;
* *Desktop:* Clientes nativos para sistemas macOS, Windows e distribuições Linux;
* *Web Player:* Acesso direto via navegadores modernos (Google Chrome, Safari, Microsoft Edge e Mozilla Firefox).

### 2. Recursos Necessários
* *Armazenamento:* Espaço livre disponível para instalação da aplicação e cache de dados de áudio baixados para reprodução offline;
* *Conectividade:* Conexão estável à internet (Wi-Fi, 4G ou 5G) para conteúdos online;
* *Hardware de Saída:* Periféricos de áudio operacionais (fones de ouvido, alto-falantes integrados ou dispositivos Bluetooth).

---

## 👥 Desenvolvedores e Liderança Executiva

| Foto / Perfil | Nome | Cargo / Papel Estratégico | Contato / Links |
| :---: | :--- | :--- | :--- |
| 👔 | **Daniel Ek** | Co-fundador e Presidente Executivo (*Executive Chairman*). Liderou a visão estratégica e expansão global da empresa desde sua fundação em 2006. | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://se.linkedin.com/in/daniel-ek-1b52093a) |
| 🛠️ | **Gustav Söderström** | Co-CEO e CPTO (*Chief Product & Technology Officer*). Responsável pela engenharia global, P&D, *design* de produto e inovação tecnológica. | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://se.linkedin.com/in/gustavsoderstrom) |
| 💻 | **Andreas Ehn** | Primeiro CTO (*Chief Technology Officer*). Responsável por recrutar os primeiros engenheiros e desenhar a arquitetura inicial da plataforma de streaming. | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://sg.linkedin.com/in/andreasehn) |
| ⚡ | **Ludvig "Ludde" Strigeus** | Principal Engenheiro de Software (criador do µTorrent). Fundamental no desenvolvimento das tecnologias de transmissão, compressão e áudio instantâneo. | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/strigeus) |



### Informações adicionais do grupo:

- Daniel Ares Gontijo Pinto
- Riquelme João dos Santos
- Nathan Gabriel Nunes dos Santos
- Isabela de Sena Alves
- Gustavo Santos de Oliveira
- João Pedro Ribeiro Otreira 
- Ryan Oliveira Trigo Santos
- Renan Oliveira Trigo Santos

