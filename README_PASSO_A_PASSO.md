# Portfólio Nando Assis - Vercel

## Arquivos principais
- `index.html` - página principal do portfólio
- `style.css` - visual do site
- `public/videos/` - 5 vídeos
- `public/pecas/` - 12 peças gráficas
- `public/pdf/` - PDF interativo
- `public/imagens/` - fotos, thumbnails e QR Code

## Passo a passo para publicar na Vercel

1. Crie uma conta em https://vercel.com
2. Instale o Node.js LTS em https://nodejs.org
3. Abra o terminal na pasta do projeto.
4. Instale a Vercel CLI:

```bash
npm install -g vercel
```

5. Faça login:

```bash
vercel login
```

6. Publique o projeto:

```bash
vercel
```

7. Responda:

```txt
Set up and deploy? Y
Which scope? escolha sua conta
Link to existing project? N
Project name? portfolio-nando
Directory? ./
Want to modify settings? N
```

8. A Vercel vai gerar um link parecido com:

```txt
https://portfolio-nando.vercel.app
```

9. Depois que tiver o link final, atualize no PDF e no QR Code, se quiser trocar o endereço provisório.

## Observação importante
O QR Code foi criado apontando para:

```txt
https://portfolio-nando.vercel.app
```

Se a Vercel gerar outro endereço, posso gerar uma nova versão com o link correto.
