# Como usar este perfil no GitHub

## 1. Crie o repositorio especial

No GitHub, crie um repositorio com o mesmo nome do seu usuario.

Exemplo:

- Usuario: `riquelmydev`
- Repositorio: `riquelmydev/riquelmydev`

O `README.md` desse repositorio aparece automaticamente no seu perfil.

## 2. Troque os placeholders

O `README.md` ja esta personalizado com:

- Usuario: `riquelmydev`
- Nome: `Riquelmy Vasconcelos`
- LinkedIn: `https://www.linkedin.com/in/riquelmyvasconcelos/`
- Email: `riquelmysvasconcelos@gmail.com`
- Projeto em destaque: `traby`

Se o projeto `traby` estiver privado ou em outra organizacao, ajuste este link no `README.md`:

```text
https://github.com/riquelmydev/traby
```

## 3. Crie o header

O header ja foi criado em:

```text
assets/header.png
```

Se quiser gerar outro manualmente, use:

https://leviarista.github.io/github-profile-header-generator/

Baixe a imagem como `header.png` e coloque em:

```text
assets/header.png
```

## 4. Ative o 3D contrib

O arquivo ja esta pronto em:

```text
.github/workflows/profile-3d.yml
```

Depois de subir para o GitHub:

1. Va em `Actions`.
2. Abra `GitHub Profile 3D Contrib`.
3. Clique em `Run workflow`.

Ele vai gerar a pasta:

```text
profile-3d-contrib/
```

## 5. Ative o Metrics

O Metrics precisa de um token pessoal.

1. No GitHub, va em `Settings` > `Developer settings` > `Personal access tokens`.
2. Crie um token.
3. No repositorio do perfil, va em `Settings` > `Secrets and variables` > `Actions`.
4. Crie um secret chamado:

```text
METRICS_TOKEN
```

5. Cole o token.
6. Rode o workflow `GitHub Metrics` em `Actions`.

## 6. Achievements

O repositorio `4xmen/Get-Github-Achievements` e um guia para conquistar badges do proprio GitHub. Ele nao e algo que voce cola diretamente no README.

As conquistas aparecem no perfil conforme voce realiza acoes no GitHub, como abrir PRs, contribuir, patrocinar projetos, criar discussoes ou manter repositorios ativos.

## Links usados

- https://github.com/yoshi389111/github-profile-3d-contrib
- https://github.com/4xmen/Get-Github-Achievements
- https://github.com/leviarista/github-profile-header-generator
- https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub
- https://github.com/antonkomarev/github-profile-views-counter
- https://github.com/tandpfun/skill-icons
- https://github.com/lowlighter/metrics
