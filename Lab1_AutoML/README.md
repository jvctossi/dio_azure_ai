Passo 1
Criar uma conta no Microsoft Azure

Passo 2
 - Acessar a plataforma do Azure em https://portal.azure.com
 - Clicar no botão "Criar um recurso"
 - Selecionar o serviço "Azure Machine Learning"

Passo 3
 - Criar um "Novo workspace"
 - Ao abrir o formulário, preencher as seguintes informações:
    - Grupo de recursos (caso não tenha, criar)
    - Nome do workspace
    - Região (Preferêncialmente - East Us)
 - Após o preenchimento, clicar em "Examinar + cirar"

Passo 4
 - No menu a direita clicar em "ML Automatizado" na sequência "novo trabalho de ML automatizado"
 - Preencher as informações fornecida pela própria microsoft (ML automated) Link:
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

Obs.: A criação pode demorar de 10 - 15 minutos, você receberá uma notificação quando finalizar.

Passo 5
 - Após a criação do modelo, você pode acessa-lo e validar o modelo clicando em "Melhor resumo do modelo" -> "Nome do algoritmo"
 - Entrar na visão de métricas e analisar os dados e gráficos

Passo 6
 - Clicar em "Implementar" -> "Serviço Web"
 - Preencher as informações descritas no link no tópico Deploy and test the model

Obs.: O deploy pode demorar de 5 - 10 minutos, você receberá uma notificação quando finalizar.

Passo 7
 - Entrar no "ponto de extremidade" criado
 - Clicar na aba "test"
 - Copiar o json fornecido na documentação e colar em "Inserir dados para teste de ponto de extremidade"
 - Clicar no botão "testar" e verificar o resultado

Passo 8
 - Deletar o ponto de extremidade conforme orientado na documentação.
