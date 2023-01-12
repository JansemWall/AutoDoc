# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação indireta dos usuários em um trabalho de imersão feita pelo product owner a partir da observação dos usuários e do registro de reclamações e sugestões.  
Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.


## Personas

|Fabrício Maia|
|Ocupação: Auxiliar Administrativo do curso de pós-graduação em Educação.|
|Frustrações|
|    • Dificuldade executar tarefas longas de forma linear.|
|    • Falta de padronização na execução de processos.|

|Cristina Filgueiras|
|Ocupação: Coordenadora do Curso de Pós-graduação em Ciências Sociais.|
|Frustação|
|    • Prazo longo para divulgação das defesas em períodos de alta demanda.|

|Tatiane Dias|
|Ocupação: Assistente do curso de pós-graduação.|
|Frustrações|
|    • Ausência de um sistema para automatizar tarefas.|
|    • Complexidade em gerar documentos manualmente.|

|Valéria das Dores|
|Ocupação: Secretária dos cursos de pós-graduação.|
|Frustrações|
|    • Falta de um sistema para geração de declarações de conclusão para discente formado.|
|    • Falta de uma mala direta utilizando mensagens “template” para toda banca.|

|Carlos Henrique|
|Ocupação: Auxiliar Administrativo do curso de pós-graduação em Ciências Sociais.|
|Frustação|
|    • Falta de um relatório com todos participantes externos em um PPG.|

|Júlia Leite|
|Ocupação: Aluna do mestrado em Ciências Sociais.|
|Frustação|
|    • Demora na divulgação da defesa.|

|Denise Figueiró|
Ocupação: Aluna do mestrado em Geografia.|
|Frustação|
|    • Divulgação de defesa com erros nos nomes dos professores externos.|

## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários. 

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|01 - Fabrício Maia| Um sistema que integre todos processos para defesa dissertação ou tese.|Para executar de forma linear o processo sem pular etapas e na geração de documentos não ter erros ortográficos.|
|02 - Cristina Filgueiras| Melhora na divulgação de defesa|Pois a divulgação com antecedência gera um aumento no engajamento nas transmissões.|
|03 - Tatiane Dias|Sistema com etapa simples|Para ter facilidade para completar o processo de defesa.|
|04 - Valéria das Dores|Um gerador de mensagens de e-mail.|Para agilizar o envio de mensagens para bancas.| 
|05 - Valéria das Dores|Busca do discente e emissão de declaração de conclusão.|Para envio por e-mail para o discente formado.|
|06 - Carlos Henrique|Geração de um relatório com todos participantes externo constando a universidade vinculada|Para registro na proposta do PPG a ser enviada a CAPES através do Sucupira|
|07 - Júlia Leite|Divulgação célere da defesa após a realização do depósito no sistema|Para compartilhar o link com amigos e familiares para assistirem a defesa.|
|08 - Denise Figueiró|Assertividade gramatical nas divulgações das defesas|Para não ocorre divulgação com nome de participante incorreto ou com vincula com universidade incorreto.|

## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais
A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01 |A aplicação deve contar campos para coletar dados do trabalho do discente e dados dos docentes.| Alta| 
|RF-02 | Gerar mensagens template com os dados da defesa para utilização por e-mail.| MÉDIA |
|RF-03 |A aplicação deve contar uma funcionalidade para geração de declaração de conclusão para o discente cadastrado|Alta|
|RF-04 |Permitir a buscar os discentes cadastrados.|Alta|
|RF-05 |A aplicação deve conter em sua página inicial um gráfico das etapas executadas e pendentes.|Alta |
|RF-06 |Gerar um relatório com todos participantes externos por programa de pós-graduação.|Média |
|RF-07 |Geração automática de peças gráficas em um template para divulgação em redes sociais. |Média |
|RF-08 |Emissão de toda documentação pertinente a defesa.|Alta |


### Requisitos não Funcionais
A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender. 
|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001 |A aplicação uma política de privacidade e disponível em uma página conforme a LGPD.|Alta |
|RNF-002 |A aplicação deve ser responsiva permitindo a visualização em um celular, tablet e monitor de forma adequada. |Alta |
|RNF-003 |O site deve ter um tempo médio de resposta para cada requisição de aproximadamente 5 segundos. |Média |
|RNF-004 |O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) |Alta |
|RNF-005 |O site precisa funcionar 24 x 7 (vinte e quatro horas por dia, sete dias por semana). |Alta |
|RNF-006 |O site deve possuir o widget do V.Libras integrado ao seu código afim de garantir acessibilidade. |Alta |



## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir. 

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01 |O projeto deve ter custo zero. |
|RE-02 |A aplicação deverá entrar em operação até dezembro de 2023. |
