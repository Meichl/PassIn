# 🎫 Pass In

**Pass In** é uma aplicação simples de **gestão de participantes em eventos presenciais**. Organizadores podem cadastrar eventos e acompanhar os participantes. Os inscritos recebem uma credencial com **QRCode** para realizar check-in no dia do evento.

---

## 📌 Funcionalidades Principais

### Para Organizadores

- Criar novos eventos
- Visualizar dados de um evento
- Listar participantes inscritos

### Para Participantes

- Inscrever-se em eventos
- Visualizar o crachá de inscrição
- Realizar check-in via QRCode

---

## ✅ Regras de Negócio

- Cada participante pode se inscrever **apenas uma vez por evento**
- Inscrições só são permitidas **enquanto houver vagas**
- O check-in pode ser feito **apenas uma vez por participante**

---

## 🛠️ Tecnologias Utilizadas

- **TypeScript**
- **Node.js**
- **Fastify**
- **SQLite**
- **QRCode**

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Node.js 18+

### Passos

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/pass-in.git
cd pass-in

# Instale as dependências
npm install

# Execute o servidor
npm run dev
