# ⚔️ Quest Study — Sistema de Missões Diárias

Sistema gamificado de acompanhamento de rotina de estudos para adolescentes. Transforma tarefas diárias em missões com XP, streaks, conquistas desbloqueáveis e recompensas semanais.

## 🎮 Funcionalidades

- **Checklist diário** com tarefas que mudam automaticamente conforme o dia da semana
- **Sistema de XP** com barra de progresso e tiers (Bronze, Prata, Ouro, Diamante)
- **Streak counter** — dias consecutivos completando missões
- **11 conquistas** desbloqueáveis com notificações animadas
- **Painel do Pai** com calendário visual, relatório semanal e cálculo automático de recompensas
- **Sistema de recompensas** por semana: R$4 (Bronze) / R$6 (Prata) / R$8 (Ouro) / R$10 (Diamante)
- **Login com email/senha** e perfis separados (Filho / Pai)
- **Sincronização em tempo real** entre dispositivos via Firebase

## 🛠️ Tecnologias

- HTML/CSS/JavaScript (vanilla, arquivo único)
- Firebase Authentication (email/senha)
- Cloud Firestore (banco de dados em tempo real)
- Google Fonts (Orbitron, Rajdhani, JetBrains Mono)

## 🚀 Como usar

Acesse o site e crie duas contas:
1. Uma conta com perfil **Pai** (acesso ao painel completo)
2. Uma conta com perfil **Filho** (acesso às missões e conquistas)

## 📋 Missões disponíveis

| Missão | Dias | XP |
|--------|------|----|
| Estudo com IA (1h) | Seg a Sex | 10 |
| Inglês Online | Seg e Qua | 10 |
| Leitura (30min) | Ter e Qui | 5 |
| Treino Caligrafia (30min) | Ter e Qui | 5 |
| Respeitou limite de tela | Todos | 5 |
| Dormiu no horário | Todos | 3-5 |
| Jiu-Jitsu | Seg e Qua | 5 |

## 🏆 Tiers e Recompensas

| Tier | % Semanal | Recompensa/Semana |
|------|-----------|-------------------|
| Bronze | 50-69% | R$ 4 |
| Prata | 70-84% | R$ 6 |
| Ouro | 85-94% | R$ 8 |
| Diamante | 95-100% | R$ 10 |

**Teto mensal: ~R$ 40-50**

---

Feito com 💜 por um pai que se importa.
