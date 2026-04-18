# 🔧 Comandos Git (Opcional)

Se você quiser usar GitHub + Cloudflare (recomendado para atualizações automáticas):

## 📋 Pré-requisitos
- Git instalado: https://git-scm.com/download/win
- Conta GitHub: https://github.com/signup

## 🚀 Comandos

### 1. Inicializar Git (na pasta do projeto)
```bash
git init
git add .
git commit -m "Initial commit - Landing Page VIP"
```

### 2. Criar Repositório no GitHub
1. Acesse: https://github.com/new
2. Nome: `landing-page-vip`
3. Deixe Public
4. NÃO marque "Initialize with README"
5. Clique "Create repository"

### 3. Conectar e Enviar
Copie os comandos que o GitHub mostrar, algo como:
```bash
git remote add origin https://github.com/SEU_USUARIO/landing-page-vip.git
git branch -M main
git push -u origin main
```

### 4. Conectar ao Cloudflare
1. Acesse: https://dash.cloudflare.com/
2. Workers & Pages → Create application
3. Pages → Connect to Git
4. Autorize GitHub
5. Selecione `landing-page-vip`
6. Deploy!

## 🔄 Para Atualizar Depois

Quando fizer mudanças:
```bash
git add .
git commit -m "Atualização da landing page"
git push
```

O Cloudflare atualiza automaticamente! 🎉

## 💡 Vantagens do GitHub

✅ Histórico de versões
✅ Deploy automático
✅ Fácil reverter mudanças
✅ Backup na nuvem

## 🆘 Problemas Comuns

### Git não reconhecido?
- Instale: https://git-scm.com/download/win
- Reinicie o terminal

### Erro de autenticação?
- Use Personal Access Token
- GitHub → Settings → Developer settings → Personal access tokens

---

**Nota:** Se preferir simplicidade, use o método de upload direto do Cloudflare!
