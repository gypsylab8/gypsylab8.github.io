# GypsyLab8 Portfolio

Site portfolio consolidado de projetos de arte, ciência e tecnologia open & free dos perfis [@gypsylab8](https://github.com/gypsylab8) e [@guimasan](https://github.com/guimasan), além de referências ao [gypsylab8.wordpress.com](https://gypsylab8.wordpress.com) e [gypsylab8.net].

## Features

- **Design robusto e profissional** com tema escuro/claro e gradientes sutis
- **Projetos em destaque** com cards estilizados, tags de linguagem e links para GitHub
- **Eixos temáticos** com ícones representando: Neurociência, Robótica, Ciência da Água, Arte Eletrônica, Sustentabilidade, Educação
- **Pesquisa em tempo real** digitando no cabeçalho (filtra projetos, posts e produções)
- **GitHub Projects grid** com filtro por linguagem e autor, com opacidade de erro de imagem
- **Blog WordPress integration** - busca os últimos 6 posts automaticamente
- **Oficinas & Arte** section
- **Produções Acadêmicas & Científicas** com lista de repositórios
- **Tema toggle** (🌙/☀️) persistente no localStorage
- **Responsive design** - funciona bem em mobile e desktop
- **Otimizado para GitHub Pages** - HTML/CSS/JS puros, nenhum build step necessário

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `gypsylab8-portfolio` ou `gypsylab8.github.io`)
2. Envie os arquivos desta pasta para a branch `main`
3. Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`
4. Acesse `https://<seu-usuario>.github.io/<repo>/`

## Atualizar projetos

Edite o array `projects` em `index.html` (dentro da tag `<script>`) para adicionar novos repositórios. Cada projeto deve ter:
- `author`: "gypsylab8" ou "guimasan"
- `name`: nome do repositório
- `desc`: descrição curta
- `lang`: linguagem principal
- `url`: URL do GitHub

As seções **Destaque** e **Temas** também podem ser atualizadas nos arrays correspondentes no script.
