# 🌀 Discord Status Bot — Hype Customizer

Um utilitário portátil e fácil de usar para Windows que permite personalizar automaticamente seu **status**, **bio** e o **emblema HypeSquad** no Discord.

---

## ✨ Funcionalidades

- ✅ Altera o **status** com frases e emojis aleatórios
- ✅ Atualiza a **bio** (Sobre Mim) do perfil
- ✅ Modifica o **emblema HypeSquad** (Bravery, Brilliance ou Balance)
- ✅ Intervalo de atualização configurável
- ✅ Tudo via arquivos `.txt` — simples e direto
- ✅ Executável — **sem necessidade de instalar Python**

---

## 🗂️ Estrutura dos Arquivos

O programa cria automaticamente os arquivos necessários na primeira execução:

- `textos.txt` → lista de frases de status (uma por linha)
- `emojis.txt` → emojis que aparecem antes do status (um por linha)
- `sobremim.txt` → textos da bio "Sobre Mim" (um por linha)
- `config.json` → onde você insere o token da sua conta

---

## 🔑 Como Configurar

1. **Execute o programa**
2. Na primeira vez, ele criará os arquivos acima
3. **Abra o arquivo `config.json`** e insira seu token manualmente:

```json
{
  "token": "SEU_TOKEN_AQUI"
}
