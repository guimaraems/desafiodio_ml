### desafiodio_ml

### Cenário: Previsão de Vendas de Guarda-Chuvas - Chuva Boa ☔

Você é responsável pela área de planejamento e vendas de uma rede varejista chamada **Chuva Boa**, especializada em artigos de proteção contra o clima, com foco principal na venda de guarda-chuvas. A rede possui lojas em diversas cidades e uma operação online crescente.  

Ao longo dos anos, você percebeu um padrão: **as vendas de guarda-chuvas aumentam consideravelmente nos dias com maior probabilidade de chuva**. No entanto, como o clima é naturalmente imprevisível, a empresa tem enfrentado dois grandes desafios:  
    - **Estoque em excesso** nos dias secos, com produtos encalhados e aumento de custos com armazenamento.  
    - **Falta de produtos** nos dias chuvosos, gerando perda de vendas e insatisfação dos clientes.  

Uma **abordagem preditiva baseada em dados climáticos** pode transformar essa realidade ao utilizar a **probabilidade de chuva** como variável para prever a **demanda diária por guarda-chuvas**, permitindo:    
    - ✅ Planejamento mais eficiente da produção e da logística  
    - ✅ Reposição proativa de estoques nas lojas e no e-commerce  
    - ✅ Redução de perdas e aumento da receita  
    
 Com a ajuda de técnicas de **Machine Learning**, você inicia o desenvolvimento de um modelo preditivo utilizando uma base de dados com 6 meses de histórico, contendo:  
    - A **data**  
    - A **probabilidade de chuva (%)** para o dia  
    - A **quantidade de guarda-chuvas vendidos**     


🔍 Como o Projeto Foi Feito   
**Geração dos Dados:** Criei um conjunto de dados simulando 182 registros com vendas de guarda-chuvas, com correlação com a probabilidade de chuva no dia.    

**Exploração Visual:** Utilizei gráficos de dispersão para entender a correlação entre as variáveis. A visualização já mostrava uma tendência clara: em dias com maior probabilidade de chuva, há uma maior venda de guarda-chuvas.  

**Modelo Preditivo:** Treinei um modelo de Regressão Linear simples com a biblioteca scikit-learn.

**Avaliação do Modelo:** Métricas como R² e MAE mostraram que o modelo teve uma boa performance.

Com ele, é possível fazer previsões rápidas, como:  

Em dias com probabilidade de chuva de 80%, anunciada na previsão metereológica, devo esperar vender quantos guarda-chuvas?  
  
🚀 Impacto Esperado  
Com o modelo em funcionamento, a Chuva Boa pode antecipar a demanda. Isso significa menos desperdício, mais eficiência, mais vendas e um time de vendas preparado para o fluxo real de clientes.  
  
E esse é só o começo: a mesma base pode ser replicada para outras futuras lojas, em diferentes localizações.

<h5 align="center">DIO - Preparação para a certificação DP 100</h5> 
