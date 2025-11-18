# Meus Resumos: Versionamento de Código com Git e GitHub

![Badge de Status](https://img.shields.io/badge/status-em%20progresso-yellow)

## ✨ Sobre o Projeto

Este repositório contém meus resumos e anotações pessoais sobre **Versionamento de Código com Git e GitHub**.

O objetivo é consolidar o conhecimento sobre as ferramentas, desde os comandos básicos até práticas de mercado, criando um guia de consulta rápida para meus futuros projetos e estudos. O material foi compilado durante meus estudos sobre o tema.

## 🚀 Status do Projeto

**Em Andamento:** Estou ativamente estudando o tema e adicionando novos resumos à medida que progrido nos tópicos.

## 📚 Tabela de Conteúdo (Resumos)

Abaixo está a tabela com os tópicos abordados e os links para os resumos detalhados de cada um.

> **Nota:** Para uma melhor organização, cada resumo está em um arquivo Markdown separado dentro da pasta `/resumos/`.

| Tópicos | Resumos Detalhados |
| :------------- | :------------- |
| Introdução ao Git e GitHub | [Resumo](./resumos/00_Introducao.md) |
| Gravando Alterações no Repositório Local | [Resumo](./resumos/01_Gravando_Alteracoes.md) |
| Trabalhando com Repositórios Remotos | [Resumo](./resumos/02_Repositorios_Remotos.md) |
| Desfazendo Alterações e Resolvendo Conflitos | [Resumo](./resumos/03_Desfazendo_Alteracoes.md) |
| O Fluxo Git (Branching) | [Resumo](./resumos/04_Branching.md) |
| *Próximo Tópico...* | *Em breve...* |

## 🛠️ Conceitos e Comandos Abordados

Durante este estudo, os seguintes conceitos e comandos principais foram documentados (e estão detalhados nos resumos acima), agrupados por funcionalidade:

### Configuração e Inicialização
* `git config`: Configura variáveis do Git (usuário, email, etc.).
* `git init`: Inicializa um novo repositório local.

### Fluxo de Trabalho Básico
* `git add`: Adiciona arquivos ao "stage" (área de preparação).
* `git commit`: Salva as alterações do "stage" no histórico local.
* `git status`: Mostra o estado atual dos arquivos (modificados, em stage, etc.).

### Análise de Histórico
* `git log`: Exibe o histórico de commits.
* `git diff`: Mostra as diferenças entre commits, branches ou arquivos.
* `git reflog`: Exibe um log de todas as movimentações do `HEAD` (extremamente útil para recuperação).

### Desfazendo Alterações
* `git restore`: Restaura arquivos no "working directory" ou "stage".
* `git reset` (soft, mixed, hard): Remove commits do histórico ou "stage" de diferentes maneiras.
* `git checkout [hash] -- [arquivo]`: Restaura um arquivo para uma versão específica.

### Repositórios Remotos
* `git clone`: Clona (baixa) um repositório remoto.
* `git push`: Envia commits locais para o repositório remoto.
* `git pull`: Busca (`fetch`) e mescla (`merge`) alterações do remoto.
* `git fetch`: Busca as alterações do remoto, mas não as mescla automaticamente.

### Branches (Ramos)
* `git branch`: Lista, cria ou deleta branches.
* `git checkout [branch]`: Muda para a branch especificada.
* `git merge`: Mescla o histórico de uma branch em outra.

### Outros
* `.gitignore`: Define arquivos e pastas que o Git deve ignorar.

### Comandos de Terminal (Auxiliares)
* `touch [arquivo]`: Cria um arquivo vazio.
* `echo "[texto]" > [arquivo]`: Escreve um texto dentro de um arquivo.

## 📘 Documentação de Referência

Como principais fontes de consulta e estudo, foram utilizadas as documentações oficiais e materiais complementares:

* [Documentação Oficial do Git](https://git-scm.com/docs)
* [Documentação Oficial do GitHub](https://docs.github.com/en/get-started)
* [Curso "Versionamento de Código" (DIO)](https://www.dio.me/) - (Material base para os estudos iniciais)

## 🧑‍💻 Autor

**[Cassiano Silverston]**

* [GitHub](https://github.com/Cassisilverston)
* [LinkedIn](https://www.linkedin.com/in/cassiano-silverston/) 

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


