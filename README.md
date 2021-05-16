<h1 align="center">Ci4 Starter</h1>

<p align="center">
  <img alt="PHP Version" src="https://img.shields.io/badge/PHP-7.3|7.4|8.0-B0B3D6?&logo=php&logoColor=#474A8A">

  <img alt="Codigniter Version" src="https://img.shields.io/badge/Codeigniter-4-B0B3D6?&logo=codeigniter&logoColor=#DD4814">

  <img alt="Testes" src="https://github.com/robsonpiere/ci4-starter/actions/workflows/testes.yaml/badge.svg">

</p>

<p align="center">
  <img alt="Principal linguagem do projeto" src="https://img.shields.io/github/languages/top/robsonpiere/ci4-starter?color=56BEB8">

  <img alt="Quantidade de linguagens utilizadas" src="https://img.shields.io/github/languages/count/robsonpiere/ci4-starter?color=56BEB8">

  <img alt="Tamanho do repositório" src="https://img.shields.io/github/repo-size/robsonpiere/ci4-starter?color=56BEB8">

  <img alt="Licença" src="https://img.shields.io/github/license/robsonpiere/ci4-starter?color=56BEB8">

  <img alt="Github issues" src="https://img.shields.io/github/issues/robsonpiere/ci4-starter?color=56BEB8" />

  <img alt="Github forks" src="https://img.shields.io/github/forks/robsonpiere/ci4-starter?color=56BEB8" />

  <img alt="Github stars" src="https://img.shields.io/github/stars/robsonpiere/ci4-starter?color=56BEB8" />
</p>

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-funcionalidades">Funcionalidades</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-pré-requesitos">Pré requisitos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/robsonpiere" target="_blank">Autor</a>
</p>

<br>

## :dart: Sobre ##

Um template  Codeigniter 4 com algumas ferramentas para qualidade de código, dependabot para atualizar as dependências e Github Actions

## :sparkles: Funcionalidades ##

:heavy_check_mark: Template inicial com Codeigniter 4;\
:heavy_check_mark: Configuração Inicial com Github Actions para seu CI;\
:heavy_check_mark: Configuração inicial do Dependabot para atualização das dependências do projeto;

## :rocket: Tecnologias ##

As seguintes ferramentas foram usadas na construção do projeto:

- [PHP](https://www.php.net)
- [Composer](https://getcomposer.org)
- [Codeigniter](https://codeigniter.com/)
- [PHPUNIT](https://phpunit.de)
- [PHPCS & PHPCBF](https://github.com/squizlabs/PHP_CodeSniffer)
- [PHPMD](https://phpmd.org)
- [PHPDOC](https://phpdoc.org)
- [PHPSTAN](https://phpstan.org)

## :white_check_mark: Pré requisitos ##

Antes de começar :checkered_flag:, você precisa ter o [Git](https://git-scm.com) e o [PHP](https://www.php.net) instalados em sua máquina.

## :checkered_flag: Começando ##

```bash
# Clone seu repositório
$ git clone https://github.com/seuusuario/seuprojeto.git nomedapasta

# Entre na pasta
$ cd nomedapasta

# Instale as dependÃªncias
$ composer install

# Para iniciar o projeto
$ php .\spark serve

# O app vai inicializar em <http://localhost:8080>
```

## :bug: Executando Testes e Ferramentas de qualidade ##

### PHPUNIT ###
```bash
$ composer test
```

### PHPCS ###
```bash
$ composer phpcs
```

### PHPCBF ###
```bash
$ composer phpcbf
```

### PHPMD ###
```bash
$ composer phpmd
```

### PHPSTAN ###
```bash
$ composer phpstan
```

## Gerar documentação ##
Necessário ter o phpdoc instalado em seu ambiente

```bash
$ composer phpdoc
```
Verifique a saida em build/docs


## :tada: Instalando em produção ##

```bash
$ composer install --no-dev --classmap-authoritative
```

## :memo: Licença ##

Este projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.


Feito com :heart: por <a href="https://github.com/robsonpiere" target="_blank">Robson Piere</a>

&#xa0;

<a href="#top">Voltar para o topo</a>
