
### Oieeeeee!  Podem me chamar Coelho ❤️

[![Insta](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white )](https://instagram.com/cecicoelho_)
[![facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/cecilia.coelho.125)


![Coelhoo GitHub stats](https://github-readme-stats.vercel.app/api?username=Coelhoo&show_icons=true&theme=white)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=coelhooooo&layout=compact)](https://github.com/coelhooo/github-readme-stats)
<br>

### Estudante de programação e cada vez gostando mais   😄 😍

![Snake animation](https://github.com/coelhooooo/coelhooooo/blob/output/github-contribution-grid-snake.svg)

Nome : Gerar Dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * */12 * * * "
  workflow_dispatch :

trabalhos :
  construir :
    nome : Jobs para atualizar dados
    run-on : ubuntu-latest
    passos :
      # Animação de Cobra
      - usa : Platane/snk@master
        id : cobra-gif
        com :
          github_user_name : coelhooooo
          svg_out_path : dist/github-contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : saída
          build_dir : dist
        ambiente :
          GITHUB_TOKEN : ${{ segredos.GITHUB_TOKEN }}
Rodapé
© 2022 GitHub, Inc.
Navegação no rodapé
Termos
Privacidade
Segurança
Status
Doc
