Procedimento para testar o modelo na Azure AI Search index (UI)

Neste laboratório você irá:

Criar recursos do Azure
Extrair dados de uma fonte de dados
Enriqueça os dados com habilidades de IA
Use o indexador do Azure no portal do Azure
Consulte seu índice de pesquisa
Revise os resultados salvos em uma Loja de conhecimento

Passo 1 
 - Acessar a sua conta no portal azure
 - Clicar em "criar um recurso"
 - Filtrar no menu a esquerda a opção "IA + Machine Learning"
 - Buscar e selecionar a opção "Pesquisa de IA"

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/0bfab2ac-5193-4364-8dfd-0632462c661b)

Passo 2
 - Clicar no botão "Criar" dentro do serviço de pesquisa
 - Preencher as informações obrigatórias
 - Alterar a opção de preço para "Básico"
 - Após finalizar todo o preenchimento, clicar no botão "Revisar + criar"

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/cd4bbeba-817d-4955-b674-a735546aa6ed)


Passo 3
 - Criar um serviço de IA
 - Voltar para o menu inicial e clicar no botão "Criar um recurso"
 - Filtrar no menu a esquerda a opção "IA + Machine Learning"
 - Clicar na opção "Serviços Cognitivos"
 - Preencher as opções obrigatórias
 - Clicar no botão "Examinar + criar"

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/18383c42-de7d-49e1-ba48-0ba13019d2f9)

Obs.: Preencher nos campos "Grupo de recursos" e "Região" o mesmo valor quando criou o "pesquisa de IA"


Passo 4
 - Criar uma conta de armazenamento (storage account)
 - Voltar para o menu inicial e clicar no botão "Criar um recurso"
 - Selcionar a opção "contas de armazenamento"
 - Clicar no botão "Criar"
 - Preencher todos os campos obrigatórios
 - Clicar no botão "Revisar + criar"

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/79aad811-34bf-47d2-8189-4ed45765ae7d)

Lembre-se de preencher as informações de acordo com a documentação fornecida pela prórpia Microsoft
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html


Passo 5
 - Acessar a conta de armazenamento
 - Selecionar a conta que você criou para o laboratório
 - No menu a esquerda procurar a opção "Configuração"
 - Habilitar a opção "Permitir acesso anônimo ao Blob"
 - Clicar na opção "Salvar"

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/f93098bc-938e-45b9-9551-a8574e030b0d)


Passo 6
 - No menu a esquerda procurar a opção "Contêineres" em Armazenamento de dados
 - Clicar no botão "+ Contêiner"
 - Digitar no campo nome coffeereviews
 - Na opção "Nível de acesso anônimo" escolher a opção "Contêiner"
 - Clicar no botão "Criar"

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/ef949b0a-cc46-4a39-be49-a348ff8cb643)


Passo 7
 - Fazer o download da pasta zip coffee reviews
https://aka.ms/mslearn-coffee-reviews
 - Selecionar o contêiner criado
 - Fazer o upload dos arquivos

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/f21f9512-68e6-4034-a2e4-56c6f013d39e)


![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/aa73872b-620f-4b7f-81b9-de68a8d5b876)


Passo 8
 - Voltar no menu inicial
 - Clicar no seu recurso de pesquisa de ia criado
 - Clicar no botão "Importar dados"
 - Preencher os campos conforme orientação da microsoft
 - Após todas as configurações e preenchimento, clicar no botão "Enviar"

![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/cfcf8825-1184-475b-a822-00d2ed165455)


Passo 9
 - Clicar na aba "gerenciador de pesquisa"
 - Executar os seguintes comandos para buscar as informações dentro do modelo
   
search=*&$count=true
search=locations:'Chicago'

- Verificar os resultados


![image](https://github.com/jvctossi/dio_azure_ai/assets/48337717/91f9e9f9-c353-4f71-b732-46c8aa2c6f97)


Obs.: Na documentação da microsoft temos outros procedimentos para implementação e melhoramento do modelo.

Lembre-se de excluir todos os recursos após os testes.

