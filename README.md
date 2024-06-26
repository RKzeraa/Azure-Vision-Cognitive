# Configuração do Azure AI Face com Azure Cognitive Services

Este guia fornece instruções sobre como configurar e usar o serviço Azure AI Face com um recurso multisserviço de serviços de IA do Azure. Se você ainda não tem um recurso de serviços de IA do Azure, siga as etapas abaixo para criá-lo.

### Passo 1: Criar um recurso de Serviços de IA do Azure

1. Acesse o [Portal do Azure](https://portal.azure.com) em uma nova guia do navegador e faça login com sua conta da Microsoft associada à sua assinatura do Azure.
2. Clique no botão **+Criar um recurso** e pesquise por "Serviços de IA do Azure".
3. Selecione **Criar um plano de Serviços de IA do Azure** e siga as configurações abaixo:
   - **Assinatura**: Sua assinatura do Azure.
   - **Grupo de recursos**: Selecione ou crie um grupo de recursos com um nome exclusivo.
   - **Região**: Leste dos EUA.
   - **Nome**: Insira um nome exclusivo.
   - **Nível de preços**: Padrão S0.
   - Marque a caixa de confirmação dos termos.
4. Selecione **Revisar + criar** e depois **Criar**. Aguarde a conclusão da implantação.

### Passo 2: Conectar o recurso ao Vision Studio

1. Acesse o [Vision Studio](https://portal.vision.cognitive.azure.com) em outra guia do navegador.
2. Faça login com sua conta e certifique-se de usar o mesmo diretório onde você criou seu recurso de serviços de IA do Azure.
3. Na página inicial do Vision Studio, selecione **Visualizar todos os recursos** no título "Introdução ao Vision".
4. Na página "Selecione um recurso para trabalhar", encontre o recurso que você criou na lista e selecione-o como recurso padrão.

### Passo 3: Detectar rostos no Vision Studio

1. Na página **inicial Introdução ao Vision**, selecione a guia **Face** e escolha **Detectar rostos em uma imagem**.
2. Leia e marque a caixa de reconhecimento da política de uso de recursos.
3. Selecione cada uma das imagens de amostra para observar os dados de detecção facial retornados.
4. Para usar suas próprias imagens, baixe [detect-faces.zip](https://aka.ms/mslearn-detect-faces) e abra a pasta no seu computador.
5. Faça upload das imagens e revise os detalhes de detecção de rosto retornados.

Além do **Detetar rostos no Vision Studio**, também utilizei o **Ler texto no Vision Studio**, e o**Analisar imagens no Vision Studio**.

#### Detetar rostos no Vision Studio
<img title="Face Detect" alt="Face detect" src="Imagens/deteccao_rostos.png">

#### Ler texto no Vision Studio
<img title="Extract Text" alt="Extract Text in img" src="Imagens/extrair_texto_img.png">

#### Analisar imagens no Vision Studio
<img title="Description Img" alt="Description img" src="Imagens/descricao_img.png">


### Limpeza

Se não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.

- Abra o portal do Azure em https://portal.azure.com e selecione o grupo de recursos que contém o recurso que você criou.
- Selecione o recurso e selecione Excluir e depois Sim para confirmar. O recurso é então excluído.

Lembre-se de que a exclusão de recursos é irreversível e pode resultar na perda permanente de dados. Certifique-se de realizar backups, se necessário.
