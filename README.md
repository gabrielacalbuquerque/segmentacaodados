# segmentacaodados
O projeto em questão foi realizado com o objetivo de realizar uma segmentação de clientes a partir da análise de recência, frequência e valor monetário e da construção do perfil desses indivíduos 

# **✔Ficha Técnica**: Projeto de Análise de Dados

---

## **📰** Análise Exploratória e Segmentação de Clientes com Base em RFM

---

**🎯 Objetivo:** 

Realizar a limpeza, preparação, análise exploratória e segmentação de clientes com base na metodologia RFM (Recência, Frequência e Valor Monetário), com visualizações interativas em dashboard.

---

**👩🏽‍🦱 Equipe:** Nesse primeiro momento, o trabalho foi **individual.**

---

**⚙ Ferramentas e Tecnologias**:

- Planilhas Google: Importação, limpeza de dados, criação de variáveis e tabelas dinâmicas.
- Fórmulas Aplicadas: IMPORTRANGE, UNIQUE, PROCV, QUERY, SE, OU, CONCATENATE, SOMA, MÊS, ANO.
- Looker Studio: Visualização de dados e construção de dashboard.

---

**💻 Processamento e análises:** 

### **🔹 Processamento e Preparação dos Dados:**

1. Importação automatizada com IMPORTRANGE e via menu “Arquivo > Importar”.
2. Exclusão de 9 registros sem id_cliente.
3. Preenchimento de 24 células vazias na coluna salário com “valores_vazios”.
4. Tratamento de 3 outliers na coluna ano de nascimento.
5. Remoção de duplicatas via ferramenta de limpeza de dados.
6. Criação de tabela consolidada de clientes e transações**.**
7. Criação de variáveis derivadas: idade, faixas etárias, faixas de salário, classe social, frequência, recência e valor monetário.

### **🔹 Análise Exploratória:**

1. Tabelas dinâmicas por estado civil, nível de escolaridade, etc**.**
2. Gráficos de colunas para visualização de variáveis categóricas.
3. Cálculo dos decis para segmentação RFM.

### **🔹 Aplicação da Segmentação RFM:**

1. Classificação automatizada com SE e OU.
2. Categorias definidas:
    - **Alta Performance:** 31 clientes.
    - **Clientes Engajados:** 156 clientes.
    - **Clientes Involutórios:** 683 clientes.
    - **Clientes Oportunistas:** 1003 clientes.
    - **Clientes Potenciais:** 339 clientes.

### **🔹 4. Visualização em Dashboard:**

1. Criação de scorecards e gráficos diversos.
2. Representação visual da segmentação de clientes.

---

**📑 Resultados e Conclusões:** 

1. Principais categorias de clientes identificadas: oportunistas, involutórios e potenciais.
2. Vinho representa 50,2% dos produtos comprados.
3. Perfil de clientes: entre 49 e 58 anos (32,4%), de classe média (56,9%), pós-graduados (50,3%), casados (38,6%) e com filhos (71,5%).

---

**🔐Limitações/Próximos Passos/recomendações**: 

1. Baixa taxa de resposta dos clientes às campanhas de marketing (15%).
2. Ajustar a segmentação com base nos perfis RFM, priorizando clientes mais recentes, frequentes. e de maior valor.
3. Personalizar as mensagens conforme o perfil comportamental dos segmentos.
4. Aplicar testes A/B em títulos, layouts e chamadas para ação.
5. Ampliar a estratégia multicanal, com reforço via WhatsApp ou SMS.
6. Acompanhar métricas por segmento, promovendo ajustes contínuos.
7. Para os Clientes de Alta Performance, recomenda-se manter a fidelidade com ofertas exclusivas, programas de pontos, e incentivos para compras contínuas.
8. Para os Clientes Potenciais, recomenda-se aumentar frequência e volume de compras com campanhas específicas ou promoções direcionadas.

---

**🔗Links de interesse:**  

- Planilha base para o tratamento de dados e posterior análise - [**LINK**](https://docs.google.com/spreadsheets/d/1pnZo6CY_Vy8I4eAhUMg25wI0G2t3ZJcBN9vXzO3E93I/edit?gid=1006076267#gid=1006076267)
- Dashboard  - [**LINK**](https://lookerstudio.google.com/reporting/2fe6d9a7-9935-4e8d-9c2f-ce074597d33e/page/ebAIF?s=n1OwdNb06_E%20)
- Apresentação da análise dos resultados - [**LINK**](https://docs.google.com/presentation/d/1Y3lXeHK4fa3Fgl7mkz5EGYzrotfpWiAxqKaam-Jp1DQ/edit#slide=id.g34daed8c64e_2_75)
