<div align="center">

<img src="./imagens/albert-einstein.png" alt="Capa" width="20%" />

 # CLFI - Físico Teórico
 
</div>

Este repositório contém todos os arquivos relacionados à apresentação de um seminário sobre física teórica para a disciplina de Introdução à Física. Aqui, você encontrará tanto a parte escrita quanto os recursos da apresentação.

## Resumo

Nossa pesquisa oferece uma visão abrangente do campo da física teórica, abordando tanto as opções educacionais disponíveis para estudantes de física quanto as atividades envolvidas na carreira de um físico teórico. Começaremos delineando as diferentes trilhas de formação disponíveis, destacando as diferenças entre os programas de licenciatura e bacharelado. Em seguida, detalharemos o percurso educacional necessário, que inclui cursos de graduação, mestrado e doutorado em física teórica.

Uma parte significativa deste estudo se concentra nas atividades cotidianas de um físico teórico, que abrangem pesquisa, experimentação, análise de dados, publicação e ensino. Exploraremos como essas atividades se entrelaçam para formar a rotina de um físico teórico, destacando a importância da pesquisa independente e da colaboração para o progresso do conhecimento científico.

No contexto brasileiro, destacaremos desafios adicionais que afetam a pesquisa científica, como limitações de financiamento, infraestrutura insuficiente e mudanças nas políticas públicas relacionadas à ciência e tecnologia. No entanto, ressaltaremos a dedicação e a paixão dos físicos teóricos brasileiros que continuam a contribuir significativamente para a física global, apesar desses obstáculos.

Nossa pesquisa concluirá enfatizando o papel fundamental dos físicos teóricos na busca pelo entendimento dos princípios fundamentais da natureza. Eles não apenas desvendam os mistérios do universo, mas também impulsionam o desenvolvimento de tecnologias inovadoras e sistemas que beneficiam a sociedade. A física teórica é uma disciplina fascinante e desafiadora que transcende fronteiras e molda o futuro do conhecimento científico. Os físicos teóricos são arquitetos do conhecimento, exploradores das fronteiras do entendimento humano e educadores que inspiram futuras gerações a continuar essa busca incessante por respostas.

## Visualização dos Arquivos

Para visualizar os arquivos gerados durante o processo de automatização, acesse [este link](https://github.com/ReinanHS/clfi-fisico-teorico/tree/gh-pages).

## Geração Manual de Arquivos

Para gerar os arquivos manualmente, siga as instruções abaixo:

1. Execute o comando abaixo para abaixar as informações do tema do slide:

```shell
wget https://raw.githubusercontent.com/reinanhs/marp-theme-academic/main/themes/academic.css
```

2. Execute o comando abaixo para gerar o slide em PDF:

```shell
docker run --rm --init -v "${PWD}:/home/marp/app/" -e LANG="pt_BR.UTF-8" marpteam/marp-cli slide-deck.md --theme academic.css --allow-local-files -o build/README.pdf
```

3. Execute o comando abaixo para gerar o texto da apresentação em PDF:

```shell
docker run --rm --init -v "${PWD}:/usr/src/trabalho" reinanhs/limarka-help:1.0.0 bin/bash -c "limarka-help"
```


## Tecnologias e Ferramentas Utilizadas

Principais tecnologias e ferramentas usadas neste projeto:

- [Limarka](https://github.com/ReinanHS/limarka-template-tcc)
- [Marp](https://marp.app/)
- [Docker](https://www.docker.com/)
- [GitHub Actions](https://docs.github.com/pt/actions)

## Changelog

Para obter informações sobre as últimas alterações no projeto, consulte [CHANGELOG](CHANGELOG.md).

## Como Contribuir

Gostaria de contribuir para este projeto? Consulte nosso guia sobre [como contribuir](CONTRIBUTING.md) para começar.

## Segurança

Se você identificar algum problema relacionado à segurança, entre em contato conosco por e-mail em [insira seu endereço de e-mail aqui] em vez de criar um problema no GitHub.

### Licença

Este projeto está sob licença. Consulte o arquivo [LICENÇA](LICENSE) para obter detalhes sobre a licença.
