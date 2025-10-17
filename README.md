# Presente de Aniversário

Projeto estático com uma página interativa que guia a escolha de um presente de aniversário.

## Estrutura

```
public/
└── index.html
vercel.json
```

## Visualizar localmente

Basta abrir `public/index.html` no navegador para testar a experiência completa.

## Deploy na Vercel

A configuração em `vercel.json` publica tudo que está dentro da pasta `public/` como site estático.

1. Instale a CLI da Vercel (`npm i -g vercel`) caso ainda não tenha.
2. Faça login: `vercel login`.
3. Na raiz do projeto, rode `vercel` para criar o projeto (responda às perguntas com os defaults ou conforme desejar).
4. Para deploys subsequentes, execute `vercel --prod`.

A Vercel servirá `public/index.html` como página principal e todo arquivo extra que você incluir nessa pasta ficará disponível na mesma URL base.
