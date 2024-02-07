# Detecção de Rostos no Azure Vision Studio

Este projeto tem como objetivo explorar os recursos de detecção facial do Azure AI Face utilizando o Azure Vision Studio. Com base nos conceitos aprendidos, realizamos a detecção de rostos em imagens para entender como essa funcionalidade pode ser aplicada em cenários práticos, como localizar clientes dentro de uma loja.

## Configuração do Projeto

### Criação do Recurso de Serviços de IA do Azure

Antes de começar, é necessário criar um recurso de serviços de IA do Azure. Siga as instruções abaixo para configurar o recurso:

1. Acesse o [Portal do Azure](https://portal.azure.com).
2. Clique em "+ Criar um recurso" e procure por "Serviços de IA do Azure".
3. Selecione "Criar um plano de serviços de IA do Azure" e configure as opções necessárias:
   - **Assinatura:** Sua assinatura do Azure.
   - **Grupo de Recursos:** Selecione ou crie um grupo de recursos com um nome exclusivo.
   - **Região:** Leste dos EUA.
   - **Nome:** Insira um nome exclusivo.
   - **Nível de Preços:** Standard S0.
4. Clique em "Revisar + criar" e, em seguida, em "Criar". Aguarde a conclusão da implantação.

A seguir, estão os print screens da criação do recurso:

- [Print Screen 01](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/config/001.jpg)

### Conexão do Recurso ao Vision Studio

Após a criação do recurso de serviços de IA do Azure, é necessário conectá-lo ao Vision Studio. Siga as instruções abaixo para realizar essa conexão:

1. Acesse o [Azure Vision Studio](https://portal.vision.cognitive.azure.com).
2. Faça login com sua conta e verifique se está usando o mesmo diretório em que criou o recurso de serviços de IA do Azure.
3. Na página inicial do Vision Studio, selecione "Exibir todos os recursos" no cabeçalho "Introdução ao Vision".
4. Selecione o recurso criado na lista e marque-o como recurso padrão.

A seguir, estão os print screens da conexão do recurso com o Vision Studio:

- [Print Screen 02](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/config/002.jpg)

### Experimentando com Imagens Fornecidas

Siga as instruções abaixo para utilizar as imagens fornecidas

1. Baixe o arquivo<a href="https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/MyFiles.zip" target="_blank">MyFiles.zip</a> contendo suas imagens.
6. Abra a pasta no seu computador e localize as imagens desejadas.
7. Carregue as imagens no Vision Studio e revise os detalhes da detecção de rosto.

A seguir, estão as imagens contidas no arquivo "**MyFiles.zip**"

- [Image 01](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/inputs/001.jpg)
- [Image 02](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/inputs/002.jpg)
- [Image 03](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/inputs/003.jpg)
- [Image 04](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/inputs/004.jpg)
- [Image 05](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/inputs/005.jpg)
- [Image 06](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/inputs/006.jpg)
- [Image 06](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/inputs/007.jpg)

Você também pode experimentar com suas próprias imagens.

## Detecção de Rostos

### Experimentando com Imagens Fornecidas

Nesta seção, vamos explorar a detecção de rostos em imagens fornecidas e observar os resultados. Siga as instruções abaixo:

1. Acesse a guia "**Rosto**" no Vision Studio.
2. Selecione o bloco "**Detectar rostos em uma imagem**".
3. Leia e concorde com a política de uso de recursos.
4. Carregue cada uma das imagens de amostra fornecidas e observe os detalhes da detecção de rosto retornados.

A seguir, estão os print screens dos resultados de "**Detectar Rostos**":

- [Print Screen 01](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/DetectFaces/001.jpg)
- [Print Screen 02](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/DetectFaces/002.jpg)
- [Print Screen 03](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/DetectFaces/003.jpg)
- [Print Screen 04](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/DetectFaces/004.jpg)
- [Print Screen 05](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/DetectFaces/005.jpg)
- [Print Screen 06](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/DetectFaces/006.jpg)

Nesta seção, vamos explorar a Analise de conteúdos em imagens fornecidas e observar os resultados. Siga as instruções abaixo:

1. Acesse a guia "**Análise das imagens**" no Vision Studio.
2. Selecione o bloco "**Adicionar legendas densas às imagens**" ou "**Adicionar legendas densas às imagens**".
3. Leia e concorde com a política de uso de recursos.
4. Carregue cada uma das imagens de amostra fornecidas e observe os detalhes do conteúdo reconhecido retornados.

A seguir, estão os print screens dos resultados de "**Adicionar Legendas**":

- [Print Screen 07](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddCaption/001.jpg)
- [Print Screen 08](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddCaption/002.jpg)
- [Print Screen 09](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddCaption/003.jpg)
- [Print Screen 010](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddCaption/004.jpg)
- [Print Screen 011](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddCaption/005.jpg)
- [Print Screen 012](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddCaption/006.jpg)
- [Print Screen 013](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddCaption/007.jpg)

A seguir, estão os print screens dos resultados de "**Adicionar Legendas Densas**":

- [Print Screen 014](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddDenseCaptions/001.jpg)
- [Print Screen 015](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddDenseCaptions/002.jpg)
- [Print Screen 016](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddDenseCaptions/003.jpg)
- [Print Screen 017](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddDenseCaptions/004.jpg)
- [Print Screen 018](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddDenseCaptions/005.jpg)
- [Print Screen 019](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddDenseCaptions/006.jpg)
- [Print Screen 020](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/AddDenseCaptions/007.jpg)

Nesta seção, vamos explorar a Analise de textos impressos nos conteúdos de imagem fornecida e observar os resultados. Siga as instruções abaixo:

1. Acesse a guia "**Reconhecimento óptico de caracteres**" no Vision Studio.
2. Selecione o bloco "**Extrair texto de imagens**".
3. Leia e concorde com a política de uso de recursos.
4. Carregue a imagem 008.jpg da amostra fornecidas e observe os detalhes dos textos reconhecidos retornados.

A seguir, estão os print screens dos resultados de "**Extrair texto de imagens**":

- [Print Screen 01](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/ExtractText/001.jpg)

## Limpeza de Recursos

Ao concluir os testes e experimentos, é importante limpar os recursos não utilizados para evitar custos desnecessários. Siga as instruções abaixo para excluir os recursos no Portal do Azure:

1. Acesse o [Portal do Azure](https://portal.azure.com).
2. Selecione o grupo de recursos que contém o recurso criado.
3. Selecione o recurso e clique em "Excluir".
4. Confirme a exclusão.

## Saiba Mais

Para obter mais informações sobre o Azure AI Face, consulte a página oficial do serviço [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html).
Para obter mais informações sobre o Azure AI Analise de Imagens, consulte a página oficial do serviço [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html).
Para obter mais informações sobre o Azure AI Reconhecimento de Caracteres, consulte a página oficial do serviço [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html).

