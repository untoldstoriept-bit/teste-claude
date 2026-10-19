# teste-claude

## Working preferences
- Responder sempre em português do Brasil.
- Quando o usuário pedir planilha/arquivo, entregar o .xlsx pronto, não só texto.
- Valores em dinheiro no formato #,##0.00 (aparece 8.890.475,45 no Excel pt-BR); quantidades em #,##0.
- Arquivos Excel: marcar applyNumberFormat/applyFont/applyFill/applyBorder="1" em todos os estilos (o programa do usuário ignora formatos sem isso) e numFmt dos gráficos com sourceLinked="0".
- Não entregar o arquivo regravado pelo LibreOffice; usar o recalc só numa cópia para conferir.
- Relatórios "SKU por vendedor": Gerente = CV, Coordenador = SV; excluir vendedores sem CV/SV; mostrar nome do vendedor (não só código) em toda linha.
- Organizar um mês por aba (JANEIRO…DEZEMBRO) e comparativos com meses em colunas na ordem Jan→Dez, verde quando sobe e vermelho quando cai.
- Nunca dividir um acumulado em meses por estimativa; pedir os relatórios mensais.
- Mês "até hoje" é parcial: marcar e não usar no crescimento do último mês fechado.
- Não somar quantidades de unidades diferentes (PC, PCT, CX, CT…) sem fator de conversão.
- Arquivos bonitos e interativos: cartões de resumo, cores, filtros, links de navegação entre abas, aba de consulta com lista suspensa, LEIA-ME explicando cada aba e termo.
- Não commitar planilhas com dados de vendas em repositório público.
