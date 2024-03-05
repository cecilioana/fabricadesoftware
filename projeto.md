<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *FIBONACCI MANAGEMENT SYSTEM*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Ana Paula Cecilio de Oliveira |Gerente de Projeto|anapaulaceciliodeoliveira900@gmail.com|
|Ana Gabriely de Oliveira |Gerente de Projeto|anagabrielyoliveira2@gmail.com|
|Isabella Mackowiak Dallabrida|Gerente de Projeto|isabellamdallabrida@gmail.com|
|Priscila Zygoski Taborda|Gerente de Projeto|pzygoski@gmail.com|
|Leticia Gabrielle Andrade Ferreira|Gerente de Projeto|lelectpm2021@gmail.com|
|Thamylla Leticia Alves de Andrade|Gerente de Projeto|lovxsininho2020@gmail.com|



# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Fibonacci Management System |
| GERENTE DO PROJETO | Wagner Ferreira |
| PRINCIPAL OBJETIVO | Auxiliar o sistema de ensino através de ferramentas síncronas e assíncronas que serão usadas por funcionários e alunos da instituição de ensino. |
| BENEFÍCIOS ESPERADOS |* Melhor acompanhamento pedagógico;<br/>* Redução da evasão escolar;<br/>* Aumento do número de matrículas;<br/>* Redução da inadimplência escolar;<br/>* Automatização dos processos financeiross|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#fibonacci-management-system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Fibonacci Management System_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à instituição e pela alocação de outros administradores|
|**Coordenador:**|Responsáveis pela aprovação de disciplinas, turmas e matrículas realizadas pela secretaria do curso, além de ser responsável pela alocação da secretaria|
|**Secretaria:**|Responsáveis pelo cadastramento de disciplinas e turmas, pela alocação de professores e monitores de um curso e matrículas dos alunos|
|**Professor:**|Responsáveis pela criação do programa da disciplina através de ferramentas de planejamento e criação de atividades|
|**Aluno:**|Seguem o programa da disciplina criada pelo professor, tendo como apoio ferramentas de comunicação, tal como: chat e fórum|


[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento


[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |Cadastrar usuario, manter e excluir | O sistema permitirá que o usuário cadastre, mantenha ou exclua o cadastro|
|RF-002 |Cadastrar pedido e manter | O sistema permitirá que o usuário cadastre ou mantenha o pedido|
|RF-003 |Cancelar pedido | O sistema permitirá que o usuário cancele o pedido |
|RF-004 |Cadastrar endereço de entrega | O sistema permitirá que o usuário cadastre o endereço de entrega |
|RF-005 |Rastrear pedido | O sistema permitirá o rastreio do pedido |
|RF-006 |Editar pedido | O sistema permitirá que o usuário edite o pedido |
|RF-007 |Emitir relatório de produtos mais vendidos | O sistema permitirá emitir o relatório dos produtos mais vendidos|
|RF-008 |Cadastrar feedback | O sistema permitirá que o usuário cadastre o feedback do pedido |
|RF-009 |Realizar pagamento |  O sistema permitirá que o cliente realize o pagamento|
|RF-010 |Cadastrar funcionários, manter e excluir| O sistema permitirá cadastrar, manter ou excluir o cadastro dos funcionários |
|RF-011 |Realizar pagamentos dos funcionários | O sistema permitirá realizar o pagamento dos funcionários |
|RF-012 |Cadastrar Ingredientes, manter e excluir | O sistema permitirá cadastrar, manter ou excluir os ingredientes quando, por exemplo, não estiver determinado produto cadastrado |
|RF-013 |Cadastrar tamanhos | O sistema permitirá cadastrar diferentes tamanhos de cupcakes |
|RF-014 |Cadastrar embalagens personalizadas | O sistema permitirá cadastrar embalagens personalizadas |
|RF-015 |Cadastrar pacotes de promoção personalizados para eventos | O sistema permitirá cadastrar pacotes de promoção personalizados para diversos eventos |
|RF-016 |Cancelar pagamento |O sistema permitirá o cancelamento do pagamento caso ocorra algum erro|
|RF-017 |Realizar entrega | O sistema permitirá realizar a entrega do produto |
|RF-018 |Cancelar entrega | O sistema permitirá cancelar a entrega do produto |
|RF-019 |Realizar vendas de cupcake | O sistema permitirá realizar vendas de cupcake |
|RF-020 |Remover produtos | O sistema permitirá remover produtos selecionados |
|RF-021 |Solicitar devolução | O sistema permitirá que o cliente solicite a devolução do produto caso ocorra algum erro |

## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Nome do Requisito |Descreva aqui as informações sobre o requisito |
|RNF-002 |Nome do Requisito |Descreva aqui as informações sobre o segundo requisito |


[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/use_case_placas.png)

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

[ [INÍCIO](#fibonacci-management-system) ]


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
