# 🌀 Discord Status Bot — Hype Customizer

Um utilitário **portátil** e fácil de usar para Windows que permite personalizar automaticamente seu **status**, **bio** e o **emblema HypeSquad** no Discord.

🔗 **Download disponível aqui:** https://github.com/viniwalkersp/Discord-HYPE/releases/tag/discordhype

---

## ✨ Funcionalidades

- ✅ Altera o **status** com frases e emojis aleatórios  
- ✅ Atualiza a **bio** (“Sobre Mim”) do perfil  
- ✅ Modifica o **emblema HypeSquad** *(Bravery, Brilliance ou Balance)*  
- ✅ Intervalo de atualização configurável  
- ✅ Tudo via arquivos `.txt` — simples e direto  
- ✅ Executável — **não precisa instalar Python ou dependências**

---

## 🗂️ Estrutura dos Arquivos

O programa cria automaticamente os seguintes arquivos na primeira execução:

- `textos.txt` → lista de frases de status (uma por linha)  
- `emojis.txt` → emojis para o início do status (um por linha)  
- `sobremim.txt` → opções de bio para o “Sobre Mim” (uma por linha)  
- `config.json` → onde você insere seu token e configurações

---

## 🔧 Como Configurar

1. **Execute o programa** (não precisa instalar nada)  
2. Ele criará os arquivos automaticamente se não existirem  
3. Abra o arquivo `config.json` e insira seu token manualmente:

```json
{
  "token": "SEU_TOKEN_AQUI"
}
