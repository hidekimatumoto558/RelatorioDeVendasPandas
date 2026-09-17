Este projeto utiliza Python (Pandas) para tratar dados de vendas e cruzar essas informações com as metas mensais dos gerentes.

##  Arquivos :
* `vendas.csv`: Histórico detalhado das vendas.
* `gerentes_lojas.xlsx`: Cadastro dos gerentes e suas metas mensais.
* `Main.ipynb`: Arquivo contendo a análise.

## Resumo do Processo dos processos
1. **Limpeza de Dados:** Correção de datas, padronização de textos e conversão de valores financeiros para números.
2. **Criação de Indicadores:** Cálculo de faturamento (Quantidade x Valor Unitário) e agrupamento de produtos por setor.
3. **Análises:** Geração de resumos de faturamento por categoria, produto e evolução mensal.
4. **Fechamento de Metas:** Cruzamento do faturamento de Março com a tabela de gerentes para verificar quem atingiu a meta.
