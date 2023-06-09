# 1. Identificação
## Identidade visual do projeto
![index](/assets/01-a-01.png)
![funcionario](/assets/01-a-02.png)
![gerente](/assets/01-a-03.png)

## Redes sociais do projeto
<div>
    <a href="https://www.instagram.com/engenhariasoftware/" target="_blank"> <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" target="_blank"></a>
    <a href="https://www.instagram.com/engenhariasoftware/" target="_blank"> <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
    <a href="https://www.instagram.com/engenhariasoftware/" target="_blank"> <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>

## Equipe

Papel | Nome
:-----: | :------:
Desenvolvedor de *Front-End* | Andre Luis Grein
Desenvolvedor de *Back-End* | Guilherme Setim


## Data criação do documento
05/06/2023



# 2. Introdução
## Objetivo do projeto
O objetivo deste projeto é construir um sistema para uma empresa de locação de veículos. A empresa em questão aluga automóveis e esta localizada longe da equipe de desenvolvimento. Ela atende um mercado apenas, o das pessoas físicas. Para acelerar o atendimento, é importante conhecer os dados de clientes que já tenham usado a locadora no passado. 

## Escopo do projeto
O Sistema de Controle de Reservas e Locações de Automóveis é uma aplicação web desenvolvida em PHP, utilizando um banco de dados MySQL, que tem como objetivo auxiliar uma empresa de locação de veículos que atendem exclusivamente o mercado de pessoas físicas.

O sistema deverá ser composto no mínimo pelos módulos Cadastro, Movimentação e Consulta. As opções que envolvem cadastramentos deverão conter as rotinas de inclusão, alteração, consulta e exclusão. 

Os layouts das telas, consultas cadastrais e gerenciais deverão ser definidas pela equipe.

### Descrição do produto (MVP) do projeto
Todos os usuários devem efetuar o login, e o sistema deve validar as entradas dos usuários.

Os usuários da categoria **funcionário** podem  realizar o cadastro de clientes e veículos e realizar consultas de clientes e veículos e filtrar veículos conforme os critérios selecionados. 

Os usuários da categoria **gerente** permite a geração de relatórios simples, proporcionando uma visão geral das informações relevantes.

### Principais entregas do projeto
- [x] Aprovação do plano de projeto
- [ ] Projeto de testes
- [ ] Integração dos módulos
- [ ] Validação do produto

### Objetivos do projeto
- [ ] Sistema sempre disponível e acessavel nos navegadores Mozilla Firefox e Chrome;
- [ ] Sistema possui credenciamento por categoria e validado;
- [ ] Sistema possui os módulos de consulta, cadastramento e gerenciamento;
- [ ] Sistema integra com os dados do sistema anterior;
- [ ] Sistema aprovado no plano de de testes proposto;

### Critérios de aceitação do produto
- [ ] Sistema possui credenciamento por categoria e validado;
- [ ] Sistema possui os módulos de consulta, cadastramento e gerenciamento;
- [ ] Sistema permite uma navegação amigável;


* **Funcionário:** [Teste login funcionário](https://quant-ux.com/#/test.html?h=a2aa10arj2gWslpVfK49EWSL2Zzhy6PuAx8zy8rbZjJJFs4XXFXgPQOVAcX2)
* **Gerente:** [Teste login gerente](https://quant-ux.com/#/test.html?h=a2aa10aWiyRKwAGU1wQSqIYSY73Oui0TL6pycLrRo4huowl8L7R7UYWpczWK)



# 3. Matriz de Riscos

Nº | Risco | Chance | Impacto | Prioridade | Análise do impacto | Ações mitigatórias / ações de contigência
:-----: | :------: | :-----: | :------: | :-----: | :------: | :-----:
1 | Falta de efetivo | Média | Alto | Alto| Equipe pequena, caso alguém fique indisponível para o projeto, ocorrerá atraso e sobrecarga aos demais. | Contratação de novos desenvolvedores para cumprir com o prazo
2 | Ampliação do escopo | Baixa | Médio | Baixo | Caso o cliente deseje ampliar o escopo, não será possível cumprir com o prazo. | Necessário negociar a ampliação do prazo de entrega do produto.
3 | Integração com os dados anteriores | Baixa | Médio | Média | Na integração com os dados anteriores, a equipe de desenvolvimento se depara com uma tecnologia que não conhece, assim dificultando a integração. | Contratação de um profissional experiente nessa tecnologia para solucionar apenas essa etapa.


# 4. Organização 
## Cronograma
Nº | Tarefa | Início | Término | Horas | Dependências | Responsável | Artefatos gerados
:-----: | :------: | :-----: | :------: | :-----: | :------: | :-----: | :-----:
1 | Fase de concepção
1.1 | Entrevista com o cliente | 03/05/23 | 03/05/23 | 3 | - | Andre | -
1.2 | Termo de Abertura | 03/05/23 | 03/05/23 | 5 | - | Andre | -
1.3 | Documento de Visão Geral | 04/05/23 | 08/05/23 | 16 | Entrevista com o cliente | Guilherme | Documento de Visão Geral
1.4 | Elaboração de plano de projeto | 08/05/23 | 08/05/23 | 6 | Documento de Visão Geral | André | Documento de Plano de Projeto
1.5 | Aprovação do plano de projeto | 10/05/23 | 10/05/23 | 3 | - | André | Versão 1.0

2 | Fase de elaboração
2.1 | Documento de requisitos | 11/05/23 | 15/05/23 | 24 | Aprovação do plano de projeto | Guilherme | Capítulo no documento de especificações
2.2 | Documento de Casos de Uso | 16/05/23 | 22/05/23 | 40 | Documento de Requisitos | Guilherme | Capítulo no documento de especificações
2.3 | Criação de protótipos | 22/05/23 | 23/05/23 | 16 | Documentos de Casos de Uso | André | Seção no documento de especificações | Interfaces no Quant UX
2.4 | Análise e validação de protótipos pelos usuários | 24/05/23 | 24/05/23 | 8 | Prototipos | André | -
2.5 | Diagramas de Sequencia | 25/05/23 | 31/05/23 | 48 | Documentos de Casos de Uso | André | Capítulo no documento de especificações
2.6 | Diagrama de classes | 01/06/23 | 05/06/23 | 24 | Diagramas de Sequencias | Guilherme | Capítulo no documento de especificações
2.7 | Plano de testes | 01/06/23 | 02/06/23 | 16 | Diagramas de Sequencia | André | Plano de teste no Quant UX
2.8 | Projeto de testes | 06/06/23 | 07/06/23 | 10 | Plano de testes | André | Link do teste no Quant UX 

3 | Fase de construção
3.1 | Desenvolvimento dos casos de uso mais complexos | 12/06/23 | 23/06/23 | 80 | Documentos de Casos de Uso; Diagramas de Sequencias; Diagrama de classes | Guilherme | Repositório no GitHub
3.2 | Testes | 23/06/23 | 23/06/23 | 2 | Desenvolvimento dos casos de uso mais complexos | Guilherme | - 
3.3 | Desenvolvimento dos casos de uso de médio e baixa complexidade | 26/06/23 | 30/06/23 | 40 | Documentos de Casos de Uso; Diagramas de Sequencias; Diagrama de classes | Guilherme; André | Repositório no GitHub
3.4 | Testes | 30/06/23 | 30/06/23 | 2 | Desenvolvimento dos casos de uso de médio e baixa complexidade | Guilherme; André | - 
3.5 | Desenvolvimento da versão final | 03/07/23 | 07/07/23 | 40 | Documentos de Casos de Uso; Diagramas de Sequencias; Diagrama de classes | André | Repositório no GitHub
3.6 | Testes | 10/07/23 | 10/07/23 | 8 | Desenvolvimento dos casos de uso de médio e baixa complexidade | André | - 
3.7 | Integração dos módulos | 11/07/23 | 14/07/23 | 32 | Desenvolvimento de todos os Casos de Uso e seus respectivos testes | Guilherme; André | Software propriamente dito
4 | Fase de transição
4.1 | Entrega do programa ao cliente | 17/07/23 | 17/07/23 | 8 | Integração dos módulos | André | -
4.2 | Implantação do sistema | 18/07/23 | 20/07/23 | 24 | Entrega do programa ao cliente | Guilherme | Software operando ao cliente
4.3 | Validação do produto | 21/07/23 | 21/07/23 | 6 | Implantação do sistema | André | -


## Organização da Equipe
Papel | Nome
:-----: | :------:
Desenvolvedor de *Front-End* | Andre Luis Grein
Desenvolvedor de *Back-End* | Guilherme Setim


## Trello
* [Link do projeto no Trello]()

# 5. Conclusão
## Recursos que serão utilizados (, ferramentas de apoio, linguagem de programação)
### Tecnologias
* Banco de dados MySql 5;
* API's de terceiros;
* Apache Server;
* Material UI;

### Serviços de terceiros
* Servidores Red Hat Enterprise Linux;

### Linguagem de programação
* PHP 8;

## Resultados esperados com o projeto desenvolvido
Através da implementação do sistema, espera-se melhorar a eficiência operacional, otimizando os processos de cadastro, consulta e gerenciamento de clientes e veículos. Isso resultará em uma gestão mais ágil e eficiente, economizando tempo e recursos.

Além disso, o sistema visa melhorar a experiência do usuário, oferecendo uma interface intuitiva e amigável. Isso facilitará a navegação e utilização por parte dos funcionários e clientes, proporcionando uma experiência mais satisfatória.

Outro resultado esperado é o aumento da produtividade da equipe. Com a automação de tarefas administrativas e operacionais, os funcionários poderão se concentrar em atividades mais estratégicas e produtivas. Isso contribuirá para um aumento geral na produtividade da locadora, maximizando o aproveitamento dos recursos humanos disponíveis.

Espera-se que o projeto traga uma vantagem competitiva para a locadora de veículos.

## Recursos para monitoração e acompanhamento do projeto
* **Quant UX:** para monitorar a experiência do usuário;
* **Plano de segurança:** para verificar os parãmetros de segurança implementado;
* **Reuniões com o cliente:** para reter o *feedback* diretamente com o cliente;