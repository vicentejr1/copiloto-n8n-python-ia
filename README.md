# 🚀 Copiloto: Automação com n8n, Python e Inteligência Artificial

## 📌 Tema
Automação avançada integrando **n8n**, **Python** e **Inteligência Artificial**.

## 🎯 Objetivo
Atuar como um especialista didático em Python, IA e n8n para orientar, passo a passo, o desenvolvimento da arquitetura de integração entre **WhatsApp**, **IA (Agente de Extração/Atendimento)** e **Google Sheets**.

---

## 📚 Fontes e Referências de Estudo

Seleção de conteúdos e tutoriais de desenvolvedores referência na área:

| Tipo | Título / Fonte | Link |
| :--- | :--- | :--- |
| 🎥 Vídeo | Integração e Automação | [Assistir no YouTube](https://youtu.be/Eaf1UxvGmlE?si=sh1TkrNRUcTAZqRq) |
| 🎥 Vídeo | Agente de IA com n8n | [Assistir no YouTube](https://www.youtube.com/watch?v=dizBEMSSzCE) |
| 🎥 Vídeo | Fluxos Avançados de Automação | [Assistir no YouTube](https://youtu.be/Tkqtd5zVkYc?si=KfIkExS_1Jk-jifJ) |
| 🎥 Vídeo | Arquitetura de Projetos em Python e IA | [Assistir no YouTube](https://youtu.be/oEiKLyjBtEQ?si=EkdwyNAtTlv2pxUj) |
| 🎥 Vídeo | Conexão WhatsApp + Webhooks | [Assistir no YouTube](https://www.youtube.com/watch?v=vvG3LjSrNN0) |
| 🎥 Vídeo | IA Generativa no n8n | [Assistir no YouTube](https://youtu.be/8czBd4isHSg?si=sxH6IYWwV9ZJRNJI) |
| 🌐 Artigo | Integração n8n e Python — *Hashtag Treinamentos* | [Acessar Artigo](https://www.hashtagtreinamentos.com/n8n-e-python) |
| 🌐 Artigo | Agente IA no WhatsApp com n8n Passo a Passo — *Expert Digital* | [Acessar Artigo](https://expertdigitaloficial.com.br/blog/agente-ia-whatsapp-n8n-passo-a-passo) |

> 🧠 **NotebookLM do Projeto:** [Copiloto Especialista](https://notebook.google.com/notebook/1da5ab28-4098-4ec0-8036-b534a3d72a2d)

---

## 👨‍🏫 Diretrizes de Comportamento do Copiloto

- **Papel:** Atuar como um professor sênior e mentor técnico hands-on.
- **Foco Didático:** Explicar a teoria e os fundamentos por trás de cada nó, código e requisição HTTP antes de partir para a execução, garantindo a fixação real do aprendizado.
- **Metodologia:** Orientação orientada a desafios práticos com resolução guiada.

---

## ❓ Perguntas Base & Guia Inicial

### 1. Qual deve ser o primeiro passo para começar a criar a aplicação de forma local (sem custos)?

> **Resposta Esperada / Ação:**
> 
> O primeiro passo é preparar o ambiente local subindo a instância do n8n (preferencialmente via **Docker**) para garantir persistência de dados e facilidade na instalação dos nós da comunidade.
> 
> **Passo a passo sugerido:**
> 1. Instalar o **Docker Desktop**.
> 2. Criar um container do n8n persistindo as variáveis de ambiente em um volume local.
> 3. Configurar a exposição do IP Público via *tunneling* (como Ngrok ou Cloudflare Tunnels) para que a API do WhatsApp consiga disparar os *Webhooks* de teste diretamente para o n8n local.

---

### 2. Para rodar o n8n localmente, é melhor usar o Windows ou uma distribuição Linux (como Ubuntu)?

> **Resposta Esperada / Comparativo:**
> 
> * **Windows:** Ideal para velocidade inicial de setup se você já usa o sistema no dia a dia. Roda perfeitamente com Docker Desktop utilizando o backend **WSL2** (Windows Subsystem for Linux).
> * **Linux (Ubuntu / Zorin OS / Linux Mint):** Excelente escolha se a prioridade for **desempenho puro e menor consumo de RAM**, já que não há o *overhead* da interface do Windows nem a camada de virtualização.
> 
> 💡 **Recomendação de Distribuição com Interface Amigável:**
> - **Ubuntu Desktop 24.04 LTS:** Estável, documentação mass
