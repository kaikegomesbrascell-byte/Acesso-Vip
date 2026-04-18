# 🔧 Comandos Completos para Subir no Vercel

## Execute estes comandos na ordem:

### 1. Inicializar Git
```bash
git init
```

### 2. Adicionar todos os arquivos
```bash
git add .
```

### 3. Fazer primeiro commit
```bash
git commit -m "Initial commit - Landing Page VIP"
```

### 4. Conectar ao GitHub
Substitua SEU_USUARIO pelo seu usuário do GitHub:
```bash
git remote add origin https://github.com/kaikegomesbrascell-byte/Acesso-Vip.git
```

### 5. Renomear branch para main
```bash
git branch -M main
```

### 6. Enviar para GitHub
```bash
git push -u origin main
```

## ✅ Pronto!

O Vercel vai detectar o push e fazer deploy automático!

---

## 🎯 OU Método Mais Fácil (Sem Git)

Se não quiser usar Git, faça upload direto:

### No Vercel:

1. Vá em: https://vercel.com/new
2. Clique em **"Browse"** ou arraste a pasta
3. Selecione a pasta do projeto
4. Configure:
   - **Output Directory:** `.`
5. Clique **Deploy**

Pronto! 🎉
