# ⚽ FUTIB — Organizador de Futebol

Painel web para organizar peladas: cadastro de jogadores, formação de equipes, placar em tempo real com cronômetro, estatísticas por jogador e ranking compartilhável por link.

🔗 **Demo:** [fut-ib-1.vercel.app](https://fut-ib-1.vercel.app)

## ✨ Funcionalidades

- **Jogadores** com cadastro e foto
- **Equipes** A e B (até 3 jogadores por time) com banco de reservas e trocas
- **Partidas** com placar, cronômetro, acréscimos e encerramento automático
- **Registro** de gols, assistências, cartões amarelos e vermelhos
- **Estatísticas** por jogador (artilheiro, assistências e cartões)
- **Ranking público** por link, com destaque para os 3 primeiros
- **Histórico** de competições

## 📸 Telas

| Partidas | Ranking público |
|---|---|
| ![Partidas](docs/partidas.png) | ![Ranking](docs/ranking.png) |

## 🛠️ Tecnologias

- HTML, CSS e JavaScript puro (sem frameworks)
- [Firebase Firestore](https://firebase.google.com/docs/firestore) para os dados
- [Firebase Authentication](https://firebase.google.com/docs/auth) (login anônimo)
- [Vercel](https://vercel.com) para publicação

## 🚀 Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/nexstzada/FutIB1.git
   cd FutIB1
   ```
2. Abra o `index.html` com a extensão **Live Server** no VS Code, ou rode qualquer servidor estático.
3. Para usar o seu próprio banco, crie um projeto no [Firebase Console](https://console.firebase.google.com), ative o **Firestore** e o **login anônimo** e substitua o bloco `firebaseConfig` no `index.html`.

## 🔐 Regras do Firestore

As regras ficam no console do Firebase. A versão usada no projeto está em [`docs/firestore.rules`](docs/firestore.rules).

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

Feito por [Nexst](https://github.com/nexstzada).
