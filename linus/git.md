[Voltar](intro.md)

# O Git

## O que é o projeto[^1]? 


O Git é um Sistema de Controle de Versões Distribuído (DVCS), esse sistema registra todas as alterações realizadas em um determinado código, dessa forma é possível visualizar todo o histórico detalhado de alterações de um projeto e, caso seja necessário, regredir a versões anteriores de forma simplificada e rápida. Foi criado por Linus Torvalds em 2005 é um sistema usado por muitos projetos de software atuais, tanto comerciais quanto Open-sources. 

O Git possui uma arquitetura distribuído, dessa froma, a cópia de trabalho de todo desenvolvedor do código é também um repositório que pode conter o histórico de todas as alterações. 

O Git oferece várias vantagens em relação ao seus concorrentes como: 

- Desempenho: os algoritmos implementados no Git aproveitam o conhecimento profundo sobre atributos comuns de árvores de arquivos de código-fonte reais, como costumam ser modificados ao longo do tempo e quais são os padrões de acesso. Dessa forma, é um sistema otimizado para desempenho. 
- Segurança: tendo a integridade do código-fonte como prioridade, o Git foi desenhado para que os conteúdos dos arquivos, seus relacionamentos, diretórios, tags, commits, entre outros, são protegidos com um algoritmo de hash de criptografia SHA1. 
- Flexibilidade: o Git é flexível, suporta a vários tipos de fluxos de trabalho de desenvolvimento não lineares, além de compatibilidade com muitos sistemas e protocolos existentes. Um exemplo de fluxo de trabalho sugerido é o GitFlow apresentado abaixo, 


![image](https://user-images.githubusercontent.com/56547429/214272903-6f55b7d7-2a8f-4ab4-a35d-b9b24ee66cf7.png)


Alguns conceitos importantes de GIT são: 

- Repositórios: ambientes criados para armazenar os códigos;
- Branch: versão/ramificação do projeto;
- Merge: comando para unir as modificações realizadas a  uma branch em questão, por exemplo, a main;
- Fork: comando que realiza a cópia do repositório em questão para um repositório próprio de quem está realizando a operação.

## Qual é ou quais são seus objetivos[^2]? 

O projeto surgiu durante o nascimento do kernel do linux, onde todas as alterações e correções eram compartilhadas em arquivos, chegaram a usar um outro software chamado DVCS para controle de versão, porém a empresa que produzia o software quebrou e começou a cobrar para usar o software, assim a comunidade (em especial o criador) viu a necessidade de ter uma ferramenta que atendesse a alguns requisitos:

- Ser rápido;
- Ser simples;
- Prover suporte não linear para o desenvolvimento (branches);
- Flexibilidade para os desenvolvedores;
- Ser distribuído;
- Ser capaz de lidar com grandes volumes de dados com eficácia e eficiência;
- Manter um rastreio para as alterações.


Para adentrar um pouco sobre seus objetivos é importante entender um pouco a razão de terem sido escolhidos e a fundamentação deles. Ser rápido e simples é uma necessidade básica uma vez que visa o desenvolvimento mais ágil, como o kernel do linux já tinha uma quantidade considerável de linhas de código então o sistema deveria ser capaz de lidar com grandes volumes de arquivos e dados, para isso foi usada uma linguagem mais próxima do baixo nível, o C, o suporte não linear é combinado com a flexibilidade para os programadores, uma vez que dessa forma é possível trabalhar isoladamente em determinados requisitos ou erros sem interferir no serviço de outra pessoa, ainda assim mantendo também o histórico de alterações para que fosse possível resgatar alterações e ficar mais fácil de reverte-las. Por fim, o sistema ser distribuido garantiu que não tivesse o problema de único ponto de falha, assim cada contribuidor poderia manter para si uma cópia do código, assim também disseminando a ideia de software Open Source.


## Como ele se relaciona com o Software Livre[^3]?

É um sistema de código aberto, distribuído sobre os termos da versão 2 da GNU General Public License (GPL).  
No site próprio site do Git (https://git-scm.com/community) no item ‘Contributing to Git’ ou ‘Contribuindo para o Git’ é possível entrar informações detalhadas dos passos para contribuir no projeto.

## Qual o status do projeto atualmente[^4]?

O projeto atualmente é uma ferramenta de código aberto amplamente utilizada e em constante desenvolvimento pela comunidade de desenvolvedores por todo o mundo, contando com 1.586 colaboradores, em sua própria página (https://git-scm.com/community) possui uma sessão destinada explicar como fazer parte da comunidade, seja enviando perguntas ou comentários, relatando algum bug, erro, problema de segurança ou até mesmo enviando uma contribuição e se tornando um colaborador do projeto. Há também uma sessão destinada a um guia sobre documentação do projeto contando com referências, livro, vídeos e links externos para auxiliar na aprendizagem da ferramenta

São lançadas novas versões e atualizações constantemente com finalidade de corrigir bugs ou atribuir novas funcionalidades ao projeto. Sua última versão oficial é Git 2.39.1, arquitetura 64 bits para Windows, lançado no dia 17/01/2023. Atualmente, o projeto também conta com ferramentas gráficas integradas, mas também pode ser obter várias ferramentas por terceiros que auxiliam na visualização do desenvolvimento de seus projetos, podendo visualizar as ramificações existentes, bem como também conteúdos como patches, árvores de arquivos, históricos de registros e revisões. Essas ferramentas gráficas podem ser instaladas tanto em computadores como também em smartphones.


[^1]: https://www.atlassian.com/br/git/tutorials/what-is-git 
  https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Uma-Breve-Hist%C3%B3ria-do-Git
  https://kenzie.com.br/blog/o-que-e-git/ 
  https://codigomaromba.com/2019/01/02/git-gitflow-usar-ou-nao-usar/
[^2]: https://learn.microsoft.com/en-us/devops/develop/git/understand-git-history
  https://about.gitlab.com/blog/2020/11/19/move-to-distributed-vcs/#:~:text=Unlike%20a%20centralized%20version%20control,workstations%2C%20creating%20multiple%20backup%20copies.
[^3]: https://www.ictea.com/cs/index.php?rp=%2Fknowledgebase%2F3484%2FiQue-es-el-software-de-control-de-versiones-GIT.html&language=portuguese-pt
  https://git-scm.com/community
[^4]: https://git-scm.com/downloads