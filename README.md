# 💇‍♀️ Hair Day - Sistema de Agendamento para Salão de Beleza

Este projeto foi desenvolvido como trabalho da disciplina de **Desenvolvimento Web**, ministrada pelo professor **Warley**, no curso de **Sistemas de Informação**.

## 📌 Descrição

O **Hair Day** é um sistema web moderno e responsivo para gerenciamento de agendamentos em salões de beleza. A aplicação foi desenvolvida utilizando **HTML5**, **CSS3** e **JavaScript vanilla (ES6+)**, com foco em boa usabilidade, organização visual e funcionalidades práticas para o dia a dia do salão.

## 🧩 Funcionalidades

- Cadastro de agendamentos por nome, data e horário
- Organização por período do dia: manhã, tarde e noite
- Cancelamento de agendamentos existentes
- Validação automática de horários e datas
- Armazenamento local dos dados com `localStorage`
- Interface responsiva para desktop e mobile
- Notificações visuais (toasts) para feedback do usuário

## 🛠️ Tecnologias Utilizadas

- **HTML5**: marcação semântica da estrutura
- **CSS3**: estilização com Flexbox e Grid Layout
- **JavaScript ES6+**: lógica da aplicação modularizada
- **LocalStorage**: persistência dos dados no navegador
- **Google Fonts**: tipografia moderna (Catamaran)

## 🗂️ Estrutura do Projeto

hair-day/
├── index.html
├── src/
│ ├── assets/ # Imagens e ícones SVG
│ ├── styles/ # CSS modularizado
│ │ ├── global.css
│ │ ├── form.css
│ │ ├── schedule.css
│ │ └── index.css
│ └── js/ # Módulos JS
│ ├── app.js
│ └── modules/
│ ├── api.js
│ ├── dom.js
│ ├── timeSlots.js
│ ├── utils.js
│ └── validation.js

markdown
Copiar
Editar

## 📱 Responsividade

- Layout em duas colunas no desktop (>1100px)
- Layout em coluna única no mobile (≤1100px)
- Fonte adaptativa entre 16px e 14px

## 🧠 Lógica de Horários

- **Manhã**: 09:00 – 12:00  
- **Tarde**: 13:00 – 18:00  
- **Noite**: 19:00 – 21:00  

## 🧪 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/michelangelo-costa/Corte-Cabelo.git
   cd Corte-Cabelo

