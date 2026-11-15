# 🍃 GreenSync - Plataforma Inteligente para Gestão e Monitoramento de Condomínios Sustentáveis

<div align="center">

[![Status do Projeto](https://img.shields.io/badge/Status-Concluído-green.svg)]()
[![Tecnologias](https://img.shields.io/badge/Techs-Node.js_%7C_Express_%7C_MySQL_%7C_Socket.IO-blue.svg)]()
[![ODS 11](https://img.shields.io/badge/ONU-ODS_11_Cidades_Sustentáveis-orange.svg)]()

Plataforma web interativa desenvolvida para auxiliar condomínios residenciais, automatizando o monitoramento de recursos e engajando moradores através de OCR e gamificação, alinhada ao Objetivo de Desenvolvimento Sustentável 11 (ODS 11).

</div>

---

## 📖 Sobre o Projeto
O **GreenSync** é um sistema de gestão participativa voltado para o monitoramento eficiente do consumo de água e energia em condomínios. O projeto soluciona a descentralização de dados e a rigidez dos registros manuais utilizando extração automatizada de faturas via **OCR**, **dashboards gráficos**, **recursos de gamificação** e **comunicação em tempo real via WebSockets**.

## Imagens do projeto

## Painel geral

<img width="1917" height="896" alt="Captura de tela 2026-09-13 160718" src="https://github.com/user-attachments/assets/5d73f888-2f1b-47f5-8b9e-7666160ea0dc" />



## Resíduos

<img width="1600" height="899" alt="WhatsApp Image 2026-10-28 at 21 09 28" src="https://github.com/user-attachments/assets/9d82e8a9-b5a6-45f2-b314-0a05365b9a5e" />



## Gamificação

<img width="1600" height="899" alt="WhatsApp Image 2026-10-28 at 21 09 29 (1)" src="https://github.com/user-attachments/assets/e4fbd5bf-3cf3-40e6-b34b-8c4a05c26cb5" />



## Comunidade

<img width="1600" height="895" alt="WhatsApp Image 2026-11-14 at 21 05 26" src="https://github.com/user-attachments/assets/c6190ded-fda2-4b29-a000-b4f46c31b325" />



## Vídeo de demonstração

https://github.com/user-attachments/assets/51f0e84b-d452-4f34-8331-494a9c75adc6

---

## ✨ Funcionalidades Principais
* **Envio de Fatura com OCR:** Extração automatizada de dados de consumo e valores monetários a partir de faturas de água e energia.
* **Dashboards Interativos:** Exibição gráfica e dinâmica do histórico de consumo individual e coletivo.
* **Gamificação e Comunidade:** Atribuição de pontos por consumo adequado, missões ativas, mural colaborativo, votações e rankings dinâmicos.
* **Guia Inteligente de Resíduos:** Classificação automatizada e orientações de descarte correto para apoio à coleta seletiva.
* **Alertas em Tempo Real:** Disparo instantâneo de notificações de anomalia caso o consumo mensal ultrapasse 30% da média histórica.

---

## 🛠️ Tecnologias Utilizadas

O sistema adota uma arquitetura web moderna estruturada nas seguintes tecnologias:

| Camada / Tecnologia | Descrição |
| :--- | :--- |
| **HTML5 / CSS3** | Estruturação e estilização responsiva das interfaces web. |
| **JavaScript (ES6+)** | Lógica de interatividade do lado do cliente. |
| **Node.js / Express** | Construção da API RESTful e gerenciamento de requisições assíncronas. |
| **MySQL** | Banco de dados relacional para armazenamento seguro de perfis, faturas e históricos. |
| **Socket.IO** | Comunicação bidirecional em tempo real para atualizações de rankings e alertas. |
| **Tesseract.js** | Biblioteca integrada para reconhecimento ótico de caracteres (OCR) nas faturas. |

---

## 📂 Estrutura do Projeto

```text
GREENSYNC/
│
├── config/             # Configurações de conexão com o banco de dados
├── controllers/        # Controladores e regras de negócio da aplicação
├── models/             # Modelos de dados e mapeamento relacional
├── public/             # Recursos estáticos (assets, estilos CSS, scripts JS)
├── routes/             # Gerenciamento de rotas da API
├── views/              # Arquivos de visualização e templates
├── index.js            # Ponto de entrada e inicialização do servidor Node.js
├── package.json        # Dependências e scripts do projeto
└── .env                # Variáveis de ambiente (não versionado)
