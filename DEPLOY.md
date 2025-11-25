# 🚀 Guia Rápido de Deploy

## Opção 1: GitHub Pages (Recomendado - GRÁTIS)

### Método Simples (Sem Git)

1. **Criar conta no GitHub** (se não tiver)
   - Acesse: https://github.com/signup
   - Crie sua conta gratuitamente

2. **Criar novo repositório**
   - Clique no botão **"+"** no canto superior direito
   - Selecione **"New repository"**
   - Nome: `instrutor-virtual`
   - Deixe como **Public**
   - NÃO marque "Add a README file"
   - Clique em **"Create repository"**

3. **Fazer upload dos arquivos**
   - Na página do repositório vazio, clique em **"uploading an existing file"**
   - Arraste TODOS os arquivos e pastas de:
     ```
     C:\Users\Mercadisc\.gemini\antigravity\scratch\instrutor-virtual
     ```
   - Inclua: `index.html`, `css/`, `js/`, `assets/`, `README.md`
   - Escreva uma mensagem: "Adicionar Instrutor Virtual"
   - Clique em **"Commit changes"**

4. **Ativar GitHub Pages**
   - Vá em **Settings** (ícone de engrenagem)
   - No menu lateral esquerdo, clique em **Pages**
   - Em **"Source"**, selecione **"Deploy from a branch"**
   - Em **"Branch"**, selecione **"main"** e pasta **"/ (root)"**
   - Clique em **"Save"**

5. **Aguardar deploy**
   - Aguarde 1-3 minutos
   - Atualize a página
   - Você verá: **"Your site is live at https://SEU-USUARIO.github.io/instrutor-virtual"**

6. **Acessar seu app**
   - Clique no link ou copie e cole no navegador
   - Pronto! Seu app está online! 🎉

---

## Opção 2: Vercel (Alternativa Rápida)

1. Acesse: https://vercel.com/signup
2. Faça login com GitHub
3. Clique em **"Add New Project"**
4. Importe o repositório `instrutor-virtual`
5. Clique em **"Deploy"**
6. Pronto! URL será: `https://instrutor-virtual.vercel.app`

---

## Opção 3: Netlify (Drag & Drop)

1. Acesse: https://app.netlify.com/drop
2. Arraste a pasta `instrutor-virtual` inteira
3. Aguarde o upload
4. Pronto! URL será: `https://random-name.netlify.app`
5. Você pode personalizar o nome nas configurações

---

## 📱 Testando em Dispositivos Móveis

Após o deploy, você pode acessar de:
- **Smartphone**: Abra o navegador e digite a URL
- **Tablet**: Mesma coisa!
- **Qualquer computador**: Funciona em Chrome, Firefox, Safari, Edge

---

## 🔄 Como Atualizar o App

### GitHub Pages:
1. Vá no repositório no GitHub
2. Navegue até o arquivo que quer editar
3. Clique no ícone de lápis (Edit)
4. Faça as alterações
5. Clique em **"Commit changes"**
6. Aguarde 1-2 minutos para atualizar

### Vercel/Netlify:
- Qualquer commit no GitHub atualiza automaticamente!

---

## ❓ Problemas Comuns

**Página não carrega:**
- Aguarde 3-5 minutos após ativar GitHub Pages
- Limpe o cache do navegador (Ctrl+Shift+R)
- Verifique se o repositório é público

**Imagens não aparecem:**
- Certifique-se de fazer upload da pasta `assets/`
- Verifique se os caminhos estão corretos

**CSS não funciona:**
- Verifique se a pasta `css/` foi enviada
- Limpe o cache do navegador

---

## 🎯 Próximos Passos

Após o deploy, você pode:
1. Compartilhar o link com alunos
2. Adicionar o link ao seu currículo
3. Continuar desenvolvendo novas features
4. Integrar com backend no futuro

---

**Precisa de ajuda?** Abra uma issue no GitHub ou me pergunte! 🚀
