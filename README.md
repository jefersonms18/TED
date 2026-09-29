CRM para Engenheiro Civil

Sistema de gerenciamento desenvolvido para auxiliar engenheiros civis autônomos no controle de clientes, projetos, obras, documentos, orçamentos e atividades administrativas.

O projeto foi desenvolvido como atividade de Trabalho Efetivo Discente (TED) da disciplina de Desenvolvimento Web.

Sobre o projeto

O CRM para Engenheiro Civil foi criado a partir da necessidade de centralizar diferentes atividades que normalmente são realizadas utilizando várias ferramentas, como planilhas, editores de texto, aplicativos de mensagens e serviços de armazenamento em nuvem.

A proposta é disponibilizar uma única plataforma para organizar informações de clientes e projetos, registrar atividades de obras, armazenar documentos, realizar cálculos e orçamentos e gerar relatórios.

 Objetivo

Disponibilizar uma plataforma centralizada para auxiliar o engenheiro civil autônomo na gestão de:

* Clientes;
* Projetos;
* Obras;
* Documentos;
* Diários de obra;
* Orçamentos;
* Informações técnicas;
* Prazos e pendências;
* Relatórios.

Funcionalidades

Dashboard

* Indicadores dos projetos;
* Acompanhamento de obras;
* Controle de prazos;
* Informações relacionadas à receita.

 Gestão de Projetos

* Cadastro de projetos;
* Organização dos projetos;
* Acompanhamento por quadro Kanban;
* Informações do cliente;
* Controle de status.

 Diário de Obra

* Registro de atividades;
* Anotações;
* Fotografias;
* Medições;
* Histórico dos registros;
* Funcionamento sem conexão com a internet;
* Sincronização posterior dos dados.

Arquivos

* Armazenamento de documentos técnicos;
* Upload e download;
* Organização por projeto;
* Versionamento dos arquivos;
* Suporte previsto para PDF, DWG e RVT.

Orçamento

* Calculadora técnica;
* Cálculos de área;
* Cálculos de volume;
* Estimativa de insumos;
* Consulta de preços utilizando o SINAPI;
* Geração de orçamentos.

 Relatórios

* Diário de Obra;
* Laudos técnicos;
* Memoriais descritivos;
* Orçamentos;
* Exportação em PDF.

 Notificações

* Alertas de prazos;
* Pendências;
* Atualizações;
* Notificações por WhatsApp.

 Personas

Engenheiro/Administrador

Profissional responsável pelo gerenciamento dos projetos e acompanhamento das obras.

Principais necessidades:

* Organizar projetos;
* Acompanhar obras;
* Registrar informações no canteiro;
* Armazenar documentos;
* Controlar versões;
* Elaborar orçamentos;
* Gerar relatórios;
* Acompanhar prazos e pendências.
 Cliente

Empresário ou proprietário da obra que recebe informações produzidas pelo sistema.

Pode receber:

* Atualizações;
* Informações sobre prazos;
* Documentos;
* Relatórios em PDF;
* Notificações pelo WhatsApp.
 Tecnologias

Front-end

* React

Back-end

* Node.js

Aplicação móvel

* React Native

Prototipagem

* Figma

A arquitetura planejada utiliza uma abordagem **Client-Server orientada a serviços REST**.

Segurança

O sistema prevê:

* Controle de acesso por perfil;
* Restrição de operações técnicas ao perfil Engenheiro/Administrador;
* Criptografia dos dados armazenados;
* Criptografia dos dados durante a transmissão;
* Backup completo diário em infraestrutura cloud.

 Responsividade e Offline

A aplicação foi planejada para funcionar em:

* Computadores;
* Tablets;
* Smartphones.

As funcionalidades de campo devem continuar disponíveis mesmo sem conexão com a internet, permitindo que os dados sejam sincronizados posteriormente.

 Estrutura planejada

  text
CRM-Engenheiro-Civil/
│
├── frontend/
│
├── backend/
│
├── mobile/
│
├── docs/
│   ├── documentacao.pdf
│   ├── wireframes/
│   └── diagramas/
│
├── README.md
└── .gitignore

 Equipe

* Gustavo Barros Martins
* Hugo Alexandre Carvalho Coelho Coutinho
* Jeferson Machado dos Santos
* Maicon de Sousa Pontes

 Documentação

A documentação do projeto apresenta:

* Identificação da equipe;
* Apresentação do projeto;
* Problema identificado;
* Objetivos;
* Personas;
* Mapa de empatia;
* Jornada do usuário;
* Requisitos funcionais;
* Requisitos não funcionais;
* Regras de negócio;
* Arquitetura da informação;
* Fluxo de navegação;
* Wireframes;
* Decisões de design;
* Arquitetura tecnológica;
* Segurança e controle de acesso.

Referências

* BASS, L.; CLEMENTS, P.; KAZMAN, R. *Software Architecture in Practice*. 4. ed. Boston: Addison-Wesley, 2021.
* ELMASRI, R.; NAVATHE, S. B. *Sistemas de Banco de Dados*. 6. ed. São Paulo: Pearson Addison Wesley, 2011.
* FOWLER, M. *UML Essencial*. 3. ed. Porto Alegre: Bookman, 2005.
* PRESSMAN, R. S.; MAXIM, B. *Engenharia de Software: uma abordagem profissional*. 8. ed. Porto Alegre: AMGH, 2016.
* RICHARDSON, L.; RUBY, S. *RESTful Web Services*. Sebastopol: O'Reilly, 2007.
* SOMMERVILLE, I. *Engenharia de Software*. 10. ed. São Paulo: Pearson Education do Brasil, 2019.
* SUTHERLAND, J. *Scrum: a arte de fazer o dobro do trabalho na metade do tempo*. São Paulo: Leya, 2014.
