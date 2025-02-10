1. Ler Texto no Vision Studio

Introdução

Neste exercício, você usará o serviço Azure AI para explorar os recursos de reconhecimento óptico de caracteres do Azure AI Vision. Você usará o Vision Studio para experimentar extrair texto de imagens, sem precisar escrever nenhum código.

O reconhecimento óptico de caracteres (OCR) é uma técnica de visão computacional para detectar e interpretar texto em imagens.

Criar um Recurso de Serviços de IA do Azure

1. Acesse o portal do Azure (https://portal.azure.com) e entre com sua conta.
2. Clique em Criar um recurso e pesquise por Azure AI services.
3. Selecione Criar um plano de serviços Azure AI.
4. Configure as opções:
   - Assinatura: Sua assinatura do Azure.
   - Grupo de recursos: Selecione ou crie um grupo de recursos exclusivo.
   - Região: Escolha a mais próxima (exemplo: "East US 2").
   - Nome: Insira um nome único.
   - Nível de preço: Padrão S0.
5. Clique em Revisar + Criar e depois em Criar. Aguarde a implantação.

Conectar ao Vision Studio

1. Acesse o Vision Studio (https://portal.vision.cognitive.azure.com).
2. Faça login e use o mesmo diretório onde criou o recurso.
3. Vá para Exibir todos os recursos na seção Introdução ao Vision.
4. Selecione o recurso criado e clique em Selecionar como recurso padrão.
5. Se necessário, atualize a página para visualizar o recurso.

Extração de Texto de Imagens

1. No Vision Studio (https://portal.vision.cognitive.azure.com), acesse Reconhecimento óptico de caracteres > Extrair texto de imagens.
2. Baixe as imagens de teste em aka.ms/mslearn-ocr-images (https://aka.ms/mslearn-ocr-images).
3. Selecione Browse for a file e carregue advert.jpg.
4. Revise os atributos detectados e visualize as caixas delimitadoras.
5. Teste com outras imagens como letter.jpg, note.jpg e receipt.jpg.

Limpeza de Recursos

Para evitar custos desnecessários:

1. Acesse o portal do Azure (https://portal.azure.com).
2. Selecione o grupo de recursos.
3. Escolha o recurso e clique em Delete, confirmando a exclusão.

---

 2. Analisar Imagens no Vision Studio

 Introdução

O Azure AI Vision permite extrair informações e entender o conteúdo de imagens. Você usará o Vision Studio para analisar imagens e testar seus recursos.

 Criar um Recurso de Serviços de IA do Azure

1. Acesse o portal do Azure (https://portal.azure.com) e faça login.
2. Clique em Criar um recurso e pesquise por Serviços de IA do Azure.
3. Escolha Criar um plano de serviços do Azure AI.
4. Configure os seguintes parâmetros:
   - Assinatura: Sua assinatura do Azure.
   - Grupo de recursos: Nome exclusivo.
   - Região: Escolha a mais próxima (exemplo: "East US 2").
   - Nome: Nome único.
   - Nível de preço: Padrão S0.
5. Clique em Revisar + Criar e depois em Criar. Aguarde a implantação.

Conectar ao Vision Studio

1. Acesse o Vision Studio (https://portal.vision.cognitive.azure.com).
2. Certifique-se de usar o mesmo diretório do recurso criado.
3. Vá para Exibir todos os recursos na seção Introdução ao Vision.
4. Selecione o recurso criado e clique em Selecionar como recurso padrão.
5. Caso o recurso não apareça, atualize a página.

Gerar Legendas para uma Imagem

1. Acesse o Vision Studio (https://portal.vision.cognitive.azure.com).
2. Vá para Análise de Imagem > Adicionar legendas às imagens.
3. Baixe as imagens de teste em aka.ms/mslearn-images-for-analysis (https://aka.ms/mslearn-images-for-analysis).
4. Carregue store-camera-1.jpg.
5. Revise a legenda gerada.
6. Teste também o recurso Legenda Densa, que fornece várias legendas com caixas delimitadoras.

Marcação de Imagens

1. Acesse Análise de Imagem > Extrair tags comuns de imagens.
2. Escolha o idioma (exemplo: English).
3. Carregue store-camera-2.jpg.
4. Revise a lista de tags extraídas e as pontuações de confiança.

Detecção de Objetos

1. Acesse Análise de Imagem > Detectar objetos comuns em imagens.
2. Carregue store-camera-3.jpg.
3. Revise os objetos detectados e suas caixas delimitadoras.
4. Ajuste o controle de Threshold value para 70 e observe as mudanças.

Limpeza de Recursos

Para evitar custos desnecessários:

1. Acesse o portal do Azure (https://portal.azure.com).
2. Selecione o grupo de recursos.
3. Escolha o recurso e clique em Delete, confirmando a exclusão.
