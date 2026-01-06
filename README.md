# Atividade-Academica---Engenharia-de-Software
## Atividade acadêmica da matéria de Engenharia de Software
Neste trabalho acadêmico foi feito a análise de requisitos funcionais e não funcionais de um pequeno sistema de almoxarifado
## REQUISITOS FUNCIONAIS:
* RF01 O sistema deve permitir selecionar um produto já cadastrado RF02 
* RF02 O sistema deve informar a quantidade recebida, data e hora da entrada. 
* RF03 O sistema deve atualizar a situação de estoque dos produtos automaticamente com base nos dados de entrada e saída 
* RF04 O sistema deverá registrar no banco de dados, quais setores solicitaram retirada de materiais do estoque, bem como a quantidade, data e hora
* RF05 O sistema deverá estar sincronizado com o sistema produtivo dos outros setores para que possa manter o controle autônomo do estoque, a fim de evitar atrasos de materiais e perdas produtivas 
* RF06 Somente funcionários autorizados do setor de almoxarifado e logística poderão ter acesso ao sistema, evitando problemas de desvio de estoque

##REQISITOS NÃO FUNCIONAIS
* RNF01 O sistema deverá estar ativo pelo tempo diário em que a empresa se mantiver em funcionamento, dependendo da sua carga horária diária/semanal, ficando fora do ar apenas nos dias que não forem úteis 
* RNF02 Todas as operações devem ser registradas em um log de auditoria contendo usuário, ação e dados alterados. 
* RNF03 O sistema deve registrar entradas e saídas mesmo em caso de falha temporária do banco, armazenando-as localmente até a reconexão. * * RNF04 Todas as movimentações devem estar disponíveis para consulta por pelo menos 3 anos 
* RNF05 Deve suportar o aumento de até 5x na quantidade de itens cadastrados sem perda de desempenho significativo 
* RNF06 O sistema deve permitir a adição de novas categorias de itens, sem necessidades de alterações estruturais no banco de dados.
  Este pequeno projeto também foi gerenciado com a ferramenta Trello, uma ferramenta de gestão de processos, onde o medelo de gestão do processo de trabalho foi feito com a metodologia Scrum..
  Também foi desenvolvido, na linguagem PYTHON um sistema simples de Gestão de Estoque de Almoxarifadon contemplando as funcionalidades exigidas pelas Regras do Negócio com os requisitos funcionais e não funcionais, onde foi codificado a importação do banco de dados (SQLite), a funcionalidade de login para usuários autorizados, identificação de produtos já cadastrados, registros de entrada e saída de produtos no sistema por setor solicitante, menu principal do sistema, execução do sistema, e as funções de cadastrar e excluir um usuário do sistema.
