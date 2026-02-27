# Portfólio Pedro Ribeiro

Site de portfólio profissional para **Pedro Ribeiro**, filmmaker, com foco em presença visual forte, layout responsivo e vitrine de conteúdos em vídeo.

## Visão Geral

Este projeto foi construído para posicionar Pedro de forma profissional desde o início da carreira, com:

- Hero de impacto com vídeo de fundo
- Seção de apresentação pessoal
- Galeria de posts/reels incorporados do Instagram
- Serviços oferecidos
- Área de contato com WhatsApp, Instagram e email
- Tema claro/escuro com alternância por botão
- Navegação responsiva com menu mobile

## Tecnologias

- `HTML5`
- `CSS3`
- `JavaScript` (vanilla)
- `Bootstrap Icons` (CDN)

## Estrutura do Projeto

```txt
Pedro-Ribeiro/
├─ index.html
├─ styles.css
├─ assets/
│  ├─ hero-video.mp4
│  └─ galeria/
│     ├─ img1.jpeg
│     ├─ img2.jpeg
│     ├─ foto-01.jpg
│     ├─ foto-02.jpg
│     ├─ foto-03.jpg
│     └─ foto-04.jpg
├─ LICENSE
└─ README.md
```

## Funcionalidades Implementadas

### 1. Hero Cinematográfico

- Vídeo de fundo (`assets/hero-video.mp4`)
- Card central com nome, frase de impacto e botões de ação
- Destaque visual com foto (`img1`) integrada ao Hero

### 2. Seção Sobre

- Texto de apresentação profissional
- Pontos de diferenciação
- Card lateral com foto (`img2`) e métricas/destaques

### 3. Portfólio em Vídeo (Instagram Embed)

- Cards com `iframe` de posts/reels do Instagram
- Controles de paginação no mobile (Anterior/Próxima)
- Layout responsivo por breakpoints

### 4. Tema Claro / Escuro

- Botão no topo com símbolo simples (`☾` / `☀`)
- Persistência no navegador com `localStorage`
- Ajustes visuais dedicados para cada tema

### 5. Contato

- WhatsApp com número configurado
- Instagram
- Email
- Formulário de contato com validação básica

## Personalização Rápida

### Alterar número do WhatsApp

No `index.html`, procure por `wa.me/` e atualize o número no formato internacional sem símbolos.

Exemplo:

```txt
https://wa.me/553598587745
```

### Alterar links dos cards de Instagram

No `index.html`, dentro da seção `.image-gallery`, altere o `src` dos `iframe` para o formato:

```txt
https://www.instagram.com/p/ID_DO_POST/embed
```

ou

```txt
https://www.instagram.com/reel/ID_DO_REEL/embed
```

### Alterar textos principais

Edite no `index.html`:

- Nome e frase principal no Hero
- Texto da seção Sobre
- Serviços
- Contatos e rodapé

### Alterar estilos

No `styles.css`:

- Cores globais via variáveis CSS (`:root`)
- Comportamento do tema escuro em `body[data-theme="dark"]`
- Espaçamentos, fontes, cards e responsividade

## Responsividade

O layout está otimizado para:

- Desktop
- Tablet
- Mobile

Com ajustes específicos para:

- Menu hambúrguer no celular
- Paginação de cards no mobile
- Redução e reorganização dos elementos do Hero

## SEO Básico

O projeto já inclui:

- `title`
- `meta description`
- `meta keywords`
- Open Graph básico
- `lang="pt-BR"`
- `meta viewport`

## Publicação (GitHub Pages)

Existem dois cenários comuns:

### Cenário A: publicar neste próprio repositório (`Pedro-Ribeiro`)

1. Vá em `Settings > Pages`.
2. Em `Build and deployment`, selecione:
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`
3. Aguarde o deploy.

### Cenário B: publicar no repositório `luisfelipepereira.github.io`

1. Copie este projeto para a pasta `Pedro-Ribeiro/` dentro do repo `luisfelipepereira.github.io`.
2. Faça commit e push no `main`.
3. Acesse:
   - `https://luisfelipepereira.github.io/Pedro-Ribeiro/`

## Execução Local

Basta abrir o `index.html` no navegador.

Opcionalmente, use um servidor local:

```bash
python -m http.server 5500
```

Depois acesse:

```txt
http://localhost:5500
```

## Licença

Este projeto está sob a licença definida no arquivo `LICENSE`.
