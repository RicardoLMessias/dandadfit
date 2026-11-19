# Wesley Danda — Landing Page de Personal Trainer

Landing page desenvolvida para o personal trainer **Wesley Danda**, cliente real. O foco é causar impacto visual logo na primeira tela e levar o visitante a agendar um horário pelo WhatsApp.

👉 **[Ver o site no ar](https://dandadfit.vercel.app)**

## Destaques

- **Animação de frames no scroll:** uma sequência de 175 imagens WebP é desenhada num `<canvas>` conforme a rolagem da página, com `requestAnimationFrame`, criando um efeito de vídeo controlado pelo usuário
- **Performance no mobile:** frames em WebP e imagem de pôster para o vídeo de fundo, pensando em carregamento rápido também no iPhone
- **Conversão:** botões de contato direto pelo WhatsApp (com mensagem pronta), Instagram e e-mail
- **Layout responsivo** com tipografia forte (Barlow Condensed + Inter)

## Tecnologias

- React
- Vite
- Canvas API
- Vercel (hospedagem)

## Estrutura

Este repositório contém o **build de produção** gerado pelo Vite (`npm run build`), que é o que a Vercel publica:

```
├── assets/   # JS e CSS empacotados + ícones
├── frames/   # 175 quadros WebP da animação de scroll
├── video/    # pôster do vídeo de fundo
└── index.html
```

## Autor

Desenvolvido por **Ricardo Lima Messias** — [GitHub](https://github.com/RicardoLMessias) · [LinkedIn](https://www.linkedin.com/in/ricardolimamessias-java)
