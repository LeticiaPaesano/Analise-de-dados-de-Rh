
# Solução de Dados para RH

Este estudo visa analisar e oferecer soluções sobre a rotatividade de funcionários em uma empresa de tecnologia. Utilizando dados internos para entender os padrões de permanência dos funcionários, identificar ciclos de rotatividade e explorar correlações entre variáveis.

### Tópicos Abordados

**Estudos e Análises:**
- Tempo médio de permanência dos funcionários.
- Ciclos de rotatividade.
- Perfil de risco dos funcionários.
- Comportamento dos funcionários com 2 anos de serviço.

### Dados Utilizados

- **Data_Contratacao**: Data exata de contratação do funcionário.
- **Data_Desligamento**: Data de desligamento do funcionário (se aplicável). Campos vazio funcionário está ativo.
- **Meses_de_Servico**: Quantidade de meses completos que o funcionário trabalhou na empresa.
- **Idade**: Idade do funcionário no momento da contratação.
- **Pontuacao_Desempenho**: Avaliação quantitativa do desempenho do funcionário (métrica de 1 a 5: 5 indica excelência nas entregas).
- **Satisfacao_Trabalho**: Nível de satisfação do funcionário com o trabalho (métrica de 1 a 5: 5 indica que o funcionário está muito feliz com o emprego).
- **Nivel_Cargo**: Hierarquia do cargo do funcionário.
- **Salario**: Salário bruto mensal do funcionário.
- **Horas_Extras**: Quantidade de horas extras trabalhadas em determinado período.
- **Desligamento**: Indica se o funcionário ainda está na empresa ou foi desligado (1 = desligado | 0 = Ativo).

### Análises e Resultados

1. **Distribuição de Desligamentos por Cargo**
   
![newplot](https://github.com/LeticiaPaesano/Analise-de-dados-de-Rh/assets/170975302/8a2ced95-c871-43be-9ae8-dbf9b54841f9)

No dia 14 de maio de 2024, a empresa enfrentou um grande número de demissões em seu quadro de funcionários. As estatísticas revelam que:
- **Junior**: 39,3% dos funcionários foram demitidos.
- **Pleno**: 31% dos funcionários foram demitidos.
- **Sênior**: 29,7% dos funcionários foram demitidos.

A maior parte dos desligamentos ocorreu no nível Junior, indicando uma possível dificuldade em reter funcionários em posições iniciais. Os níveis Pleno e Sênior também apresentam uma alta taxa de desligamentos, sugerindo que a retenção é um problema em todos os níveis da empresa.

**Sugestão de Melhoria:**
- Implementar programas de treinamento e desenvolvimento de carreira para os funcionários Junior.
- Expandir marcos de serviço, reconhecimento e incentivos, especialmente para cargos Pleno e Sênior.

2. **Contratações ao Ano**
   
![newplot 1](https://github.com/LeticiaPaesano/Analise-de-dados-de-Rh/assets/170975302/af2198ce-24df-424b-bb09-47732b4cbcd8)


Houve um aumento nas contratações de 2021 a 2023, seguido de uma queda significativa em 2024.

**Análise:**
A queda nas contratações em 2024 pode estar relacionada a políticas de contenção de custos ou uma mudança na estratégia de contratação.

**Sugestão de Melhoria:**
- Avaliar as causas da queda nas contratações e ajustar as estratégias de recrutamento se necessário.
- Considerar iniciativas de branding de empregador para atrair novos talentos.

3. **Tempo Médio de Permanência dos Funcionários**
   
![newplot 2](https://github.com/LeticiaPaesano/Analise-de-dados-de-Rh/assets/170975302/9d3e497c-d749-4b4c-a3d2-053aab293733)

A análise do tempo médio de permanência dos funcionários é fundamental para entender a retenção de talentos e identificar áreas que necessitam de melhorias.

**Análise:**
- Funcionários contratados mais recentemente tendem a ter menos meses de serviço.
- O tempo médio de permanência dos funcionários na empresa é de aproximadamente 19 meses.
- O tempo máximo de permanência registrado foi de 35 meses.

**Pontos Críticos:**
A análise pode ajudar a identificar períodos críticos onde a retenção de funcionários pode estar em risco. Por exemplo, há um aumento significativo na rotatividade após os funcionários atingirem entre 18 e 19 meses de serviço.

**Sugestão de Melhoria:**
- Implementar programas de desenvolvimento de carreira para incentivar a retenção a longo prazo.
- Oferecer incentivos e benefícios adicionais para funcionários que ultrapassam a marca de 18 meses de serviço.
- Implementar um sistema de reconhecimento juntamente ao feedback já existente para reconhecer e incentivar o bom desempenho dos funcionários.

  ### Conclusão

Este estudo não apenas identificou áreas de melhoria cruciais para a retenção de talentos, mas também forneceu sugestões estratégicas para promover um ambiente de trabalho mais estável e motivador. Implementar essas recomendações não apenas pode reduzir a rotatividade, mas também fortalecer a cultura organizacional e aumentar a produtividade dos colaboradores.


