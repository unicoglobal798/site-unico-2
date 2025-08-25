
# ÚNICO – site pronto para publicar (gratuito)

Este pacote contém seu `index.html` (exatamente como você enviou), duas imagens *placeholders* com os nomes esperados (`logo_unico.jpeg` e `familia_feliz.jpg`), um `404.html` e arquivos de configuração opcionais para **Netlify** e **Vercel**.

> Troque os *placeholders* pelas suas imagens reais quando quiser: basta substituir os arquivos mantendo os mesmos nomes.

---

## Opção 1 – GitHub Pages (100% grátis)

### A) Pelo navegador (sem terminal)
1. Crie uma conta em https://github.com (se ainda não tiver).
2. Clique em **New** para criar um repositório. Nome sugerido: `unico-site` (pode ser outro).
3. Entre no repositório e clique em **Add file → Upload files**.
4. Faça *upload* de **todos os arquivos** desta pasta (inclusive `index.html`, imagens e `404.html`).
5. Vá em **Settings → Pages** (barra lateral).
6. Em **Build and deployment**, escolha **Deploy from a branch**.
7. Em **Branch**, selecione `main` e a pasta **/** (root). Clique **Save**.
8. Em alguns instantes aparecerá a URL do seu site, por exemplo:  
   `https://SEU-USUARIO.github.io/unico-site/`

> Dica: Para usar o seu domínio (ex.: `assineunico.com.br`), crie um arquivo `CNAME` na raiz com o domínio e aponte o DNS (registro CNAME) para `SEU-USUARIO.github.io`.

### B) Com Git (opcional)
```bash
git init
git remote add origin https://github.com/SEU-USUARIO/unico-site.git
git add .
git commit -m "Publica site ÚNICO"
git push -u origin main
```
Depois ative o **Pages** em *Settings → Pages* como descrito acima.

---

## Opção 2 – Netlify (grátis, domínio *.netlify.app)
1. Acesse https://app.netlify.com e crie conta.
2. Clique em **Add new site → Deploy manually**.
3. Arraste e solte **esta pasta** na página de upload.
4. O site vai subir com um subdomínio tipo `https://nome-aleatorio.netlify.app`.  
   Você pode personalizar o subdomínio nas configurações do site.
5. Arquivo `netlify.toml` já incluso (simples).

---

## Opção 3 – Vercel (grátis, domínio *.vercel.app)
1. Acesse https://vercel.com e crie conta.
2. Clique em **Add New… → Project** e selecione o seu repositório (se subiu no GitHub) **ou** use **Deploy** arrastando a pasta.
3. O site ganhará um subdomínio em `*.vercel.app`.  
   Arquivo `vercel.json` já incluso (simples).

---

## Observações
- Seu `index.html` usa **Font Awesome** via CDN, então não é preciso instalar nada.
- Se quiser alterar as imagens, mantenha os nomes: `logo_unico.jpeg` e `familia_feliz.jpg` (na raiz).
- Para WhatsApp, os links com `wa.me` já estão configurados no HTML.
- Este é um site 100% estático (HTML/CSS/JS), ou seja: ideal para hospedagem gratuita e permanente.
