🍦 Previsão de Vendas de Sorvete

Modelo de machine learning que prevê o volume de vendas de sorvete a partir da temperatura registrada em cada dia. O projeto foi construído no Azure Machine Learning Studio, usando um pipeline completo sem código.

🎯 Objetivo

Entender a relação entre temperatura e vendas de sorvete e usar essa relação para estimar vendas futuras com base em previsões climáticas, ajudando no planejamento de estoque e produção.

🛠️ Tecnologias
Azure Machine Learning Studio (Designer)
Regressão linear
Dataset sintético (100 dias de registros)
📋 O que foi feito
Criação do dataset: geração de um conjunto de dados sintético com 100 dias, contendo temperatura e vendas.
Análise exploratória: estudo da relação entre temperatura e vendas.
Treinamento: modelo de regressão linear treinado no Azure Machine Learning Studio.
Pipeline: configuração e execução do pipeline completo, sem escrever código.
Avaliação: visualização dos resultados e das métricas de desempenho.
📊 Principais resultados
Temperaturas acima de 30°C aumentam consideravelmente as vendas.
O modelo consegue prever vendas futuras a partir de previsões de temperatura.
<!-- Se quiser, adicione aqui as métricas do seu modelo (ex.: R², MAE, RMSE) e um print do gráfico de temperatura x vendas. -->
🚀 Como reproduzir
Crie um workspace no Azure Machine Learning Studio.
Registre o dataset de temperatura e vendas.
No Designer, monte o pipeline: dataset → divisão treino/teste → regressão linear → treinamento → avaliação.
Execute o pipeline e confira as métricas na etapa de avaliação.
Use o modelo treinado para gerar previsões com novas temperaturas.
🔮 Próximos passos
Testar com dados reais de vendas.
Incluir outras variáveis, como dia da semana, feriados e umidade.
Comparar com outros algoritmos de regressão.
Publicar o modelo como endpoint para previsões em tempo real.
👤 Autor

José Carlos Da Silva Júnior
