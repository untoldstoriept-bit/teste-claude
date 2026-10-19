# teste-claude

## Working preferences
- Responder sempre em português do Brasil.
- Quando o usuário pedir planilha/arquivo, entregar o arquivo pronto, não só texto.
- Nunca colocar dados de empresa (nomes, valores, relatórios, estrutura da equipe) neste repositório: ele é público. Esses detalhes ficam só na conversa.
- Valores em dinheiro no formato #,##0.00 (aparece 8.890.475,45 no Excel pt-BR); quantidades em #,##0.
- Arquivos Excel: marcar applyNumberFormat/applyFont/applyFill/applyBorder="1" em todos os estilos e numFmt dos gráficos com sourceLinked="0"; não entregar arquivo regravado pelo LibreOffice (recalcular só uma cópia para conferir).
- Séries mensais: um mês por aba e comparativos com meses em colunas na ordem Jan→Dez, verde quando sobe e vermelho quando cai; mês parcial marcado e fora do crescimento do último mês fechado.
- Nunca dividir um total acumulado em meses por estimativa; pedir os dados mensais.
- Não somar quantidades de unidades diferentes sem fator de conversão.
- Planilhas bonitas e interativas: cartões de resumo, cores, filtros, links entre abas, aba de consulta com lista suspensa e LEIA-ME explicando cada aba e termo.
