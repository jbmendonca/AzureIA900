# AzureIA900
preparatório AI-900
1. Configurar o Workspace do Azure ML
Acesse o Portal do Azure e faça login.
No menu esquerdo, clique em "Criar um recurso".
Pesquise por "Machine Learning" e selecione "Workspace Machine Learning".
Preencha os detalhes necessários, como nome, grupo de recursos e região.
Clique em "Revisar + Criar" e confirme a criação.
2. Criar e Configurar um Experimento
Após a criação, acesse o workspace e abra o Azure Machine Learning Studio.
Na aba "Dados", clique em "+ Criar" para preparar os dados.
Insira o nome, descrição e tipo de dados, e faça o upload do arquivo de entrada.
Verifique e registre o dado com um nome, como "bike-rentals".
Utilize o aprendizado de máquina automatizado para treinar um modelo:
Crie um novo trabalho de ML automatizado.
Configurações básicas: nome do trabalho, descrição, tipo de tarefa (regressão), e conjunto de dados.
Selecione o conjunto de dados "bike-rentals" para continuar.
3. Avaliar o Modelo
Na guia "Visão geral do trabalho de aprendizado de máquina automatizado", observe o resumo do melhor modelo.
Avalie as métricas de desempenho e escolha o modelo mais adequado.
4. Implantar o Modelo
Crie um endpoint:
No Azure Machine Learning Studio, navegue até a seção de endpoints.
Clique em "Criar endpoint" e preencha os detalhes necessários.
Selecione o modelo treinado e configure o endpoint para inferências em tempo real.
5. Testar o Endpoint
Teste o endpoint para garantir que está funcionando corretamente.
Utilize dados de teste para verificar as previsões e ajuste conforme necessário.
6. Monitorar e Atualizar
Monitore o desempenho do modelo e do endpoint.
Realize atualizações e re-treinamentos conforme necessário para manter a precisão das previsões.
