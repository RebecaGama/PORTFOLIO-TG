<h1 align="center"> 3° Semestre - 1/2023 </h1>
<p align="center">
  <a href ="#sobre-o-projeto"> Sobre o projeto  </a>  • 
  <a href ="#requisitos"> Requisitos </a>  • 
  <a href ="#tecnologias-utilizadas"> Tecnologias Utilizadas </a>  •
  <a href ="#contribuições-pessoais"> Contribuições Pessoais </a>  
</p>
<br>

## Sobre o projeto 

<div align="justify">
  Parceiro acadêmico: Visiona
  <br><br>
  O projeto tem como objetivo o desenvolvimento de um Sistema de Gerenciamento de Usuários, com um serviço robusto de autenticação e autorização. A solução será implementada utilizando a arquitetura de microserviços, aproveitando a infraestrutura e as ferramentas disponíveis na Google Cloud Platform (GCP). A implementação será feita através de containers, com integração e entrega contínuas utilizando uma esteira de CI/CD (Integração Contínua/Entrega Contínua).
  <br><br>
  Durante o desenvolvimento, serão seguidas as melhores práticas de Desenvolvimento Orientado a Objetos (OOP), com foco em princípios como SOLID, Clean Code e Clean Architecture, garantindo a manutenção e escalabilidade do sistema. Além disso, serão realizados testes unitários e de integração, com o objetivo de assegurar a qualidade da entrega, e a cobertura de código deverá ser de pelo menos 80%, validada por ferramentas de análise de código, como o SONAR ou outra ferramenta equivalente.
  <br><br>
  O sistema contará com uma interface para gerenciamento de usuários, permitindo funcionalidades como a criação, visualização, edição e remoção de usuários, além da atribuição de permissões específicas a cada usuário, conforme as necessidades da aplicação.
<div><br>

#### Problemas

- **Gestão Manual de Usuários**: A gestão de usuários era realizada manualmente, o que gerava inconsistências, dificuldades de controle e aumento do risco de erros na atribuição de permissões.
- **Segurança e Autenticação**: A falta de um sistema estruturado de autenticação e autorização criava vulnerabilidades, especialmente em ambientes com diferentes níveis de acesso e permissões entre os usuários.
- **Escalabilidade e Manutenção**: O sistema não era escalável nem fácil de manter, o que dificultava a adaptação às necessidades crescentes da organização e a aplicação de atualizações constantes.

#### Soluções

- **Automatização e Centralização do Gerenciamento de Usuários**: A implementação de um sistema baseado em microserviços, com containers, permitiu uma gestão centralizada e automatizada dos usuários. Cada ação, como a criação, edição ou remoção de usuários, foi automatizada, eliminando inconsistências e facilitando o controle.
  
- **Segurança Reforçada com Autenticação e Autorização**: Foi integrado um serviço de autenticação/autorização robusto, utilizando padrões modernos de segurança, como **OAuth** e **JWT**. Isso garantiu que somente usuários autorizados tivessem acesso às funcionalidades do sistema, com permissões específicas definidas de acordo com o perfil de cada um.

- **Escalabilidade e Manutenção com Microserviços**: Ao adotar a arquitetura de microserviços e containers, o sistema se tornou escalável e de fácil manutenção. Cada componente foi isolado e pode ser modificado ou atualizado independentemente, sem impactar outros módulos do sistema.

- **Qualidade e Confiabilidade com Testes e CI/CD**: A equipe implementou testes unitários e de integração, garantindo que as funcionalidades do sistema estivessem sempre funcionando corretamente. O uso de uma esteira de CI/CD assegurou entregas contínuas e rápidas, com alta qualidade de código validada por ferramentas de análise.

> [Repositório oficial do projeto](https://github.com/atomofatec/API-VISIONA).

<br>

https://github.com/RebecaGama/PORTFOLIO-TG/assets/102360635/b4a9f310-257e-4996-87cb-bfea26736df0

> Projeto finalizado.

<br>
  
## Requisitos 
 
**Funcionais:**<br>
 - Ao acessar o sistema, login e senha, o usuário deve ser direcionado para a listagem de usuários cadastrados. Caso contrário, deverá ser retornada mensagem de erro, e o usuário deve continuar na tela de login.
- Cadastro de novos usuários.
- Edição de usuários já cadastrados.
- Visualização de todos os usuários cadastrados em forma de lista. Os campos apresentados devem ser nome, perfil de acesso, status de criação, e se está ativo.
- Possibilidade de desativar um usuário (exclusão lógica).
- Funcionalidade de ‘esqueci minha senha`. Deve ser enviado e-mail com token, para que o usuário possa criar nova senha no sistema

**Não Funcionais:**<br>
- Documentação de todo o sistema. Modelagem de banco, e código fonte
- Manual do usuário
- Utilização do GCP
- Utilização de ferramentas para CI/CD (Git, GihubAction, Jenkins, Sonar)
- Criação de componentes para reaproveitamento de código.

<br>

## Tecnologias Utilizadas
Ao longo do projeto, foram trabalhados com as seguintes ferramentas:
<br>
  - **Discord:** Para reuniões;
  - **WhatsApp:** Para troca de mensagens e avisos;
  - **HTML5:** Marcação do layout e importação dos componentes do website; 
  - **CSS3:** Estilização o site;
  - **JavaScript:** Animações e interações com o usuário;
  - **NodeJS:** Desenvolvimento back-end;
  - **PostgreSQL:** Armazenamento e manipulação de dados;
  - **Figma:** Criação do protótipo navegável;
  - **Canva:** Edição das imagens e criação das apresentações;
  - **Github:** Controle de versão;
  - **Visual Studio Code:** IDE para o desenvolvimento.
  
<br>

## Contribuições Pessoais

**Desenvolvimento de Interfaces e Front-End**  
Atuei como desenvolvedora responsável pela construção das interfaces da aplicação, focando em usabilidade e clareza visual, com JavaScript. Durante o projeto, fui responsável pela criação e implementação das seguintes funcionalidades:

- **Tela de Login:** Desenvolvi a tela de login, incluindo validações de autenticação, para garantir uma experiência segura e eficiente aos usuários no acesso à aplicação.
- **Tela de Cadastro de Usuário:** Implementei a funcionalidade completa de cadastro de novos usuários, com validações de dados obrigatórios e de formato, assegurando que os dados fossem devidamente processados e armazenados.
- **Tela de Edição de Usuário:** Criei uma interface de edição de usuários, permitindo que informações já registradas fossem modificadas de forma intuitiva e segura, com feedback visual para ações bem-sucedidas.
- **Listagem de Usuários Cadastrados:** Desenvolvi uma tela de listagem, onde os usuários cadastrados são exibidos de forma organizada, incluindo opções de filtragem e ordenação para facilitar a navegação e o gerenciamento de dados.

Além disso, colaborei na criação do protótipo visual das interfaces, garantindo que os elementos fossem consistentes com a identidade visual do projeto e contribuíssem para uma navegação intuitiva.

**Colaboração no Backend**  
Embora meu foco fosse no front-end, participei da integração de funcionalidades entre o front-end e o back-end. Contribuí especificamente na criação de endpoints para o cadastro e edição de usuários, garantindo que as interações entre as interfaces e o servidor ocorressem sem falhas.

**Controle de Versão e Gestão no GitHub**  
Mantenho o controle de versão e a gestão do código no GitHub, fazendo commits frequentes para registrar mudanças nas funcionalidades e assegurar que todas as atualizações fossem documentadas e rastreáveis para a equipe.

<br>

## Hard Skills
  - **Dominio de HTML5:** Sei fazer com autonomia;
  - **Dominio de CSS3:** Sei fazer com autonomia;
  - **Manipulação de entradas com Javascript:** Sei fazer com autonomia;
  - **NodeJS:** Sei fazer com auxílio de consultas;
  - **Utilização do PostgreSQL:** Sei fazer com auxílio de consultas; 
  - **Criação de Wireframe com Figma:** Sei fazer com autonomia;
  - **Edição de imagens com Canva:** Sei fazer com autonomia;
  - **Controle de versão com o Github:** Sei fazer com autonomia.


## Soft Skills

**Criatividade**  
Durante o desenvolvimento do protótipo, enfrentei um desafio em que o design inicial não atendia às necessidades dos usuários. Sugeri uma abordagem criativa para melhorar a navegação, propondo uma reorganização dos elementos da interface e adicionando funcionalidades intuitivas. Esse ajuste ajudou a equipe a alcançar uma solução mais prática e visualmente atraente, alinhada às expectativas do cliente.

**Organização**  
Em uma das sprints, houve um imprevisto que impactou o cronograma do projeto. Adotei uma abordagem organizada para reestruturar as minhas tarefas prioritárias, ajustando prazos e definindo novas metas junto ao time. Esse esforço garantiu que conseguíssemos compensar o atraso sem comprometer a qualidade da entrega final.

**Colaboração**  
Durante um momento crítico do projeto, um colega enfrentava dificuldades técnicas que afetavam o progresso das entregas. Ofereci suporte realizando uma sessão conjunta de troubleshooting, compartilhando meu conhecimento sobre a ferramenta e ajudando a resolver o problema. Essa colaboração contribuiu para o sucesso da sprint e fortaleceu o trabalho em equipe. 
