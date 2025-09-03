## International Schools BI Dashboard (INEP Data)

## Objetivo
Explorar dados educacionais do INEP para gerar insight a uma escola privada bilingue no Brasil.  
O projeto resultará em um **dashboard BI**.

## Estrutura do Projeto
- `data/` → datasets (não versionados no GitHub)
- `notebooks/` → notebooks de exploração
- `requirements.txt` → dependências
- `README.md` → documentação do projeto

## Stack
- Python (Pandas)
- Jupyter Notebook
- PostgreSQL
- Power BI


## Roadmap dos dados a serem apresentados no BI:
Perguntas a serem respondidas:

Tamanho de mercado: Vale a pena investir em privadas? Onde?

Perfil do público: O público selecionado (Urbano, classe média/alta, disposto a pagar por qualidade) é realmente o melhor público de acordo com os dados?

Concorrência: Onde estão as escolas privadas? O mercado está saturado ou aberto?

Diferenciação: Podemos competir oferecendo turmas menores, mais professores por aluno, ensino premium bilíngue? 



1. Participação de Mercado – Públicas vs Privadas

Métrica: % de escolas privadas no total.

Por que importa:
Mostra tamanho do mercado privado no Brasil. Se for pequeno em certas regiões, pode indicar barreiras (ex.: renda, regulação). Se for grande, mostra que existe um mercado consolidado e competitivo.

Insight esperado: Definir regiões prioritárias para expansão da rede bilíngue.

2. Localização Urbana x Rural (Privadas)

Métrica: % de escolas privadas em áreas urbanas x rurais.

Por que importa:
Escolas bilíngues têm público-alvo urbano, ligado a famílias com maior poder aquisitivo.
Um gráfico confirmando que o mercado é massivamente urbano ajuda a validar foco de expansão em grandes cidades.

Insight esperado: Reforçar estratégia urbana e identificar exceções (municípios rurais com demanda diferenciada).

3. Total de Matrículas em Escolas Privadas (por Estado / Município)

Métrica: Soma de QT_MAT_BAS.

Por que importa:
O número de alunos mostra tamanho real da demanda paga.
Estados/municípios com mais matrículas privadas são mercados mais maduros, com maior capacidade de absorver escolas bilíngues.

Insight esperado: Priorizar expansão em estados/municípios com maior concentração de alunos privados.

4. Alunos por Professor (Indicador de Qualidade)

Métrica: Média = Alunos ÷ Professores.

Por que importa:
Mostra a qualidade percebida das escolas privadas. Uma relação mais baixa sugere ensino mais individualizado.
Como escola bilíngue, manter baixo esse índice é diferencial de marketing (“turmas menores, mais atenção”).

Insight esperado: Comparar se a rede bilíngue pode oferecer uma proporção melhor que a média do mercado → argumento comercial forte.

5. Alunos por Turma (Indicador de Lotação)

Métrica: Média = Alunos ÷ Turmas.

Por que importa:
Complementa o indicador de qualidade. Turmas superlotadas podem indicar insatisfação dos pais → oportunidade para escolas com proposta premium.

Insight esperado: Mostrar que há espaço para diferenciação oferecendo turmas menores, com foco em imersão no inglês.

6. Mapa de Distribuição de Escolas Privadas (por Estado/Município)

Métrica: Contagem de escolas privadas.

Por que importa:
Permite ver geograficamente onde está a concorrência e onde há espaços pouco explorados.
Pode revelar mercados saturados x mercados em crescimento.

Insight esperado:

Saturação em grandes capitais = alta concorrência, foco em diferenciação.

Municípios médios com alta renda, mas poucas privadas = oportunidade de entrada.

