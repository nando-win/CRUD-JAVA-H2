
Tecnologias:
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

> Fase 01 - Regras
1. Clonar esse repositório com a estrutura basica da Api.
2. Criar duas branchs *develop* e *feature/crud-seunome* tudo deve ser desenvolvido na branch *feature/crud-seunome* depois realizado um merge para *develop*.
3. O prazo de enviar o código é de **48hs** a partir do compartilhamento do repositório
4. Enviar para repositório após concluir
> informações do projeto: 
- Banco de dados: **H2**
- Console H2: /h2-console
- Usuario de acesso ao banco de dados: **user**
- Password de acesso ao banco de dados: **password**

> Fase 02 - Estruturar API
5. A porta padrão do projeto deve ser ser 9090
6. O context-path da aplicação de ser */api*
> Fase 03 - Rotas
7. Cadastrar Pessoas /  Cadastrar Setor
8. Atualizar Pessoa / Atualizar Setor
9. Deletar Pessoas / Deletar Setor
10. Listar Pessoas / Listar Setor
11. Todas as rotas devem ser validadas
> Fase 04 - Segurança
12. Configurar uma Autenticação básica *(Basic Authentication)*
13. Desativar a segurança para a rota de *Listar Pessoas*
> Fase 05 - Testes
14. Implemente classes de teste usando o framework *jUnit* ou *Mockito* teste no minimo 5 rotas;
> Fase 06 - Deploy
15. Gere uma imagem docker e envie para o https://hub.docker.com/
> Fase 07 - Bonus
* 15.1\. documente a API usando Swagger


