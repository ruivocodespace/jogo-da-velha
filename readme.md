# Jogo da Velha 🎮

Jogo da Velha desenvolvido em **Python**, executado no terminal e projetado para dois jogadores.

> ✅ Projeto desenvolvido como parte do curso **Python Essentials 1** da **Cisco Networking Academy**.

---

## 🚀 Funcionalidades

- Modo para dois jogadores (X e O)
- Validação de jogadas
- Verificação automática de vitória
- Detecção de empate
- Estrutura modular organizada em múltiplos arquivos

---

## 🧠 Visão Técnica

O projeto foi estruturado com separação de responsabilidades, dividindo a lógica do jogo em arquivos diferentes para melhor organização e manutenção do código.

### 📂 Estrutura do Projeto

- `main.py` → Fluxo principal do jogo e interação com os jogadores  
- `check_winf.py` → Lógica de verificação de vitória ou empate  
- `check_impf.py` → Validação de jogadas  
- `print_tabf.py` → Função responsável por exibir o tabuleiro  

---

## ▶️ Como Executar

1. Certifique-se de ter o **Python 3.x** instalado.
2. Clone o repositório:
   ```bash
   git clone https://github.com/ruivocodespace/jogoDaVelha.git
   cd jogoDaVelha
   python main.py
