# 🏆 Brasileirão Amigável

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![NextAuth.js](https://img.shields.io/badge/NextAuth.js-FFFFFF?style=for-the-badge&logo=nextauthdotjs&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

O **Brasileirão Amigável** é uma plataforma web criada para amigos que querem apostar em palpites de placares do Campeonato Brasileiro. O objetivo é oferecer uma **experiência divertida, competitiva e social**, onde cada usuário pode testar seu conhecimento sobre futebol, acompanhar resultados e competir com amigos em rankings personalizados.

---

## 🎯 Objetivos

- Criar uma **competição saudável entre amigos**, com rankings e pontuações.
- Permitir que os usuários façam **palpites de partidas** de forma rápida e intuitiva.
- Fornecer **estatísticas e histórico** de palpites para análise de desempenho.
- Manter a experiência **simples, gamificada e envolvente**, estimulando a participação contínua.

---

## 💡 Funcionalidades Principais

### Autenticação e Perfil

- Login seguro através do **Google**.
- Gestão de perfil com **nome, avatar e estatísticas pessoais**.
- Acompanhamento de performance histórica de palpites.

### Palpites e Jogos

- Visualização de **jogos da rodada atual, próxima e passada**.
- Criação de palpites com **pontuação automática** baseada no resultado oficial: (Pode ser alterada de acordo com as configurações do admin)
  - 5 pontos: acerto exato
  - 3 pontos: acerto de vencedor/empate sem exato
  - 1 ponto: erro
- Palpites bloqueados após o início das partidas, garantindo **justiça e integridade**.

### Grupos e Rankings

- Criação e participação em **grupos privados ou públicos**.
- Ranking interno de cada grupo para estimular a competição entre amigos.
- **Ranking global** para acompanhar os melhores palpites de todos os usuários.

### Estatísticas e Feedback

- Indicadores claros sobre **quantidade de palpites, acertos exatos, acertos parciais e erros**.
- Feedback visual direto sobre a precisão dos palpites (cores e indicadores intuitivos).
- Histórico detalhado de partidas e desempenho para análise contínua.

### Mensagens ao Admin

- Permite que usuários enviem mensagens diretamente ao administrador do sistema.
- Facilita comunicação sobre problemas, dúvidas ou sugestões.
- As mensagens são registradas e notificam o admin para resposta rápida.

---

## 🛠️ Tecnologias Utilizadas

- **Next.js 15 (App Router)** – Framework moderno e performático.
- **React** – Interface dinâmica e responsiva.
- **Tailwind CSS** – Estilização elegante e adaptativa.
- **Prisma** – ORM robusto para gerenciamento do banco de dados.
- **NextAuth.js** – Autenticação segura e integrada.
- **TypeScript** – Tipagem estática para maior confiabilidade.
- **PostgreSQL/MySQL** – Banco de dados relacional.

---

## 🌟 Experiência do Usuário

O site é pensado para ser **intuitivo e engajador**, permitindo que usuários:

1. Entrem rapidamente e vejam os jogos disponíveis.
2. Realizem palpites de forma prática, sem complicações.
3. Acompanhem seu desempenho e o de amigos com rankings claros.
4. Sintam-se motivados a participar continuamente graças à gamificação e feedback visual.
5. Criem e gerenciem grupos para competir com amigos, tornando a experiência social e divertida.

---

## 🚀 Como Rodar o Projeto - Ainda não disponível

Siga os passos abaixo para clonar e executar o projeto localmente:

### Pré-requisitos

- Node.js >= 20
- npm ou yarn
- Banco de dados PostgreSQL ou MySQL

### Passos

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/brasileirao-amigavel.git
cd brasileirao-amigavel
```

2. Instale as dependências

```bash
npm install
```

3. Configure variáveis de ambiente

```bash
Crie um arquivo `.env` com as chaves do banco de dados e do NextAuth.js e preencha com seus dados de acordo com o arquivo `.env.example`.
```

4. Gere o client do Prisma e aplique migrations

```bash
npx prisma generate
npx prisma migrate dev
```

5. Inicie o projeto

```bash
npm run dev
```

### Abra no navegador

```
http://localhost:3000
```

O **Brasileirão Amigável** é mais que um site de apostas: é uma experiência **social, divertida e competitiva**, perfeita para quem ama futebol e quer disputar com amigos de forma saudável.
