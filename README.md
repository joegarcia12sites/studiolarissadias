# Studio Larissa Dias — Pilates e Fisioterapia

Aplicação web institucional e sistema de agendamento online interativo desenvolvido para o **Studio Larissa Dias — Pilates e Fisioterapia** (Rua Alto da Cruz, ao lado da Tropical Suplementos).

## Funcionalidades

- **Agendamento Online Inteligente:** Sincronizado em tempo real com o calendário (Segunda a Sexta-feira) e com o relógio local para bloqueio automático de horários ultrapassados.
- **Regras de Turnos Automatizadas:**
  - **Manhã (Seg a Sex):** 08h às 12h
  - **Tarde (Seg a Sex):** 14h às 17h
  - **Noite (Seg e Sex):** 18h às 20h
- **Painel Administrativo (CMS Integrado):** Controle de visibilidade de seções, edição visual inline de textos e imagens, gestão de serviços, planos, equipe e tópicos rápidos de WhatsApp.
- **Arquitetura Híbrida de Persistência:** Suporte a exportação de `index.html` estático pré-configurado e sincronização em tempo real via nuvem (Firebase Realtime Database / JSONBin / REST).

## Tecnologias Utilizadas

- HTML5 Semântico
- Tailwind CSS (via CDN v3.4.17)
- Vanilla JavaScript (ES6+)
- Hospedagem contínua (CI/CD) via GitHub + Vercel