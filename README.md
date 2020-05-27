
## Tecnologias utilizadas

Nessa solução deve utilizada as seguintes tecnologias:
- Java 1.8
- Maven
- SpringBoot 2+
- Git
- H2 Data Base
- Mockito
- jUnit
- Swagger
## Desafio
> Objetivo
- O RH da empresa solicitou a equipe de Sistemas uma aplicação para gerenciar informações dos colaboradores da empresa.
Seu objetivo é desenvolver uma API Rest para que a equipe de front-end realize as consultas nos endpoints e retorne as informações solicitadas pelo RH.
Crie a API seguindo as orientações abaixo:
> Regras
- Projeto de conter duas branchs *develop* e *feature/crud-seunome* tudo deve ser desenvolvido na branch *feature/crud-seunome* depois realizado um merge para *develop*.
- O prazo de enviar o código é de **48hs** a partir do compartilhamento do repositório
- Enviar o repositório após concluir
- Caso não conclua no prazo, informar em qual fase e item você conseguiu chegar.
> Fase 01 - Estruturar Projeto: 
1. Criar o projeto java usando maven para gerenciamento de suas dependencias.
2. Configure o Banco de dados: **H2** em seu projeto
3. Configure o Console H2 para : /console
4. Usuario de acesso ao banco de dados: **user**
5. Password de acesso ao banco de dados: **password**
6. O projeto deve conter duas entidades pessoas e setor. A entidade pessoas deve conter os dados referente ao colaborador. A entidade setor deve conter os dados do setor refente a 
pessoa cadastrada.
> Fase 02 - Estruturar API
7. A porta padrão do projeto deve ser ser 9090
8. O context-path da aplicação de ser */api*
> Fase 03 - Rotas da API
9. Cadastrar Pessoas /  Cadastrar Setor
10. Atualizar Pessoa / Atualizar Setor
11. Deletar Pessoas / Deletar Setor
12. Listar Pessoas / Listar Setor
13. Todas as rotas devem ser validadas
> Fase 05 - Testes
14. Implemente classes de teste usando o framework *jUnit* ou *Mockito* teste no minimo 5 rotas;
> Fase 06 - Segurança
15. Configure uma Autenticação básica *(Basic Authentication)*
> Fase 08 - Deploy
16. Gere uma imagem docker e envie para o https://hub.docker.com/
> Fase 09 - Bonus
* 16.1\. documente a API usando Swagger


