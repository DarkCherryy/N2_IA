# Execucao de teste: triagem contabil

## Objetivo
Preparar uma ficha administrativa para o relato ficticio CONT-TESTE-001.

## Dados de entrada
- `apoio/clientes_ficticios.md`
- `apoio/tabela_assuntos.md`

## Instrucao ao agente
Classifique o relato usando somente uma categoria da tabela de assuntos.
Registre os fatos informados, dados ausentes, urgencia informada, perguntas
pendentes e recomendacao de encaminhamento. Nao responda a duvida fiscal nem
deduza regime tributario, cadastro ou prazo.

## Saida esperada
Uma ficha em `saida/fichas_triagem/`, identificada como preliminar e sujeita
a revisao humana.

## Excecoes e limites
Nao prestar consultoria contabil, fiscal ou juridica. Encaminhar qualquer
incerteza relevante ao associado humano.

## Revisao humana
O associado responsavel revisa a ficha antes de qualquer resposta ou
encaminhamento ao cliente.
