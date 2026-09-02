# Publicando o Site de Triagem em Saúde

Este repositório contém um site completo de **Acolhimento Humanizado e Triagem em Saúde** desenvolvido para o DPE-GO.

## 🚀 Como Publicar

### Opção 1: GitHub Pages (Recomendado - Gratuito)
1. Vá às configurações do repositório → **Settings**
2. Procure por **Pages** no menu lateral
3. Em "Source", selecione `main` branch e `/root` folder
4. Clique em **Save**
5. Seu site estará disponível em: `https://supervisaolozandes01-art.github.io/triagemsaude/`

### Opção 2: Netlify (Gratuito com Deploy Automático)
1. Acesse [netlify.com](https://netlify.com)
2. Clique em **New site from Git**
3. Conecte seu repositório GitHub
4. Configure: Branch `main`, Build command deixar vazio, Publish directory `/`
5. Clique em **Deploy**

### Opção 3: Vercel (Gratuito)
1. Acesse [vercel.com](https://vercel.com)
2. Clique em **New Project**
3. Importe o repositório GitHub
4. Clique em **Deploy**

## 📋 Estrutura do Projeto

```
.
├── index.html          # Site completo (aplicativo web)
├── README.md          # Descrição do projeto
└── PUBLICACAO.md      # Este arquivo
```

## ✨ Recursos do Site

- ✅ Sistema completo de triagem em saúde
- ✅ Acolhimento humanizado
- ✅ Interface responsiva
- ✅ Temas claro/escuro
- ✅ Sem dependências externas

## 🔧 Desenvolvimento Local

Para testar o site localmente, simplesmente abra o arquivo `index.html` em um navegador:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Ou use um servidor local:
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js
npx http-server
```

Depois acesse: `http://localhost:8000`

## 📱 Compatibilidade

- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablet
- ✅ Mobile

---

**Próximas etapas:** Escolha uma das opções de publicação acima e seu site estará online em minutos!
