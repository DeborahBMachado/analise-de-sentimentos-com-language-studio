# Analise-de-sentimentos-com-language-studio

Esse repositório contém uma breve introdução das funcionalidade de fala e linguagem da IA de Machine Learning do Azure, dando uma melhor embassamento no âmbito de leitura de um texto, e com base nele ter uma análise das emoções.

# Speech Studio
1. Acesse (https://speech.microsoft.com/portal) e clique em "engrenagem" no canto superior direito
2. Você será direcionado para a aba de configurações, como não existe nenhum recurso para isso, clique em "Criar novo recurso"
3. Insira o nome do recurso, o tipo de preço que será o padrão S0 (o gratuito) e o grupo de recursos (caso não tenha, existe a opção de criar um) e apertar no botão Azure para criá-lo
4. Para utilizar é preciso selecionar e clicar em "usar o recurso"
5. Agora, vamos usar a ferramenta. Para isso desça a tela até a opção de "Conversão de fala em texto em tempo real" e clicar no link azul
6. Assim que entrar nessa funcionalidade, o sistema irá identificar o recurso criado e selecionado. Depois vai pedir uma confirmação que isto poderá gastar crédito da sua conta. Em relação a questão da caixa de seleção, ela se refere a que idioma é o arquivo.
7. Na parte debaixo terá de um lado uma seção você passar um arquivo de aúdio (ou gravar um aúdio) e do outro lado a demonstração do resultado em tempo real (para ser feito isso, é somente clicar no botão que está em pause e resumí-lo)

# Language Studio
O Language Studio (https://language.cognitive.azure.com/) tem um objetivo semelhante ao Speech Studio, contudo o enfoque dele é na leitura de documentos ou textos, em que ele irá analizá-los e retornar dados como conversão de texto para fala, tradução e entre outros.

1. Entre no portal do azure, depois clique em criar um novo recurso ou create a new resource, escolher a categoria AI + Machine Learning e dessa vez escolher o Language Service e clicar no criar ou create
2. Seguir em frente pelo continue to create your resource ou continuar para criar o seu recurso (não é necessário alterar nada)
3. Você deve colocar o grupo de recurso, o nome, o tier de preço e selecionar a caixa de seleção do nota de uso responsável de IA e clicar em Review + Create e depois em create
4. Finalizando a criação de recursos, você deve ir ao Language Studio. Ao ir para lá, ele pedirá para você pedir o tipo de recurso (nesse caso o Language) e o nome do recurso criado agora à pouco e clicar em done
5. Na tela inicial do estúdio, vá para o item Analyze sentiment and mine opinions (Analizar sentimento e opiniões)
6. É nessa funcionalidade que se verifica e demonstra os sentimentos da pessoa que criou o texto, dando notas de porcentagem de sentimentos/emoções positivas, neutras e negativas, junto com a porcentagem de certeza e as palavras de cada frase que a demonstram

# Finalizando
Finalizando, é possível ver um leque de opções para utilizar o Speech ou Language Studio, ou também integrar os dois ou acrescentar o de reconhecimento de imagens também.
