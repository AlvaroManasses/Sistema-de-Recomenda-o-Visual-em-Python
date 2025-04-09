## Este código:

Usa a arquitetura ResNet50 pré-treinada para extração de características

Normaliza os embeddings usando L2-normalization

Utiliza Annoy para indexação eficiente de similaridade

Implementa busca por similaridade de cosseno

Mostra resultados visuais com matplotlib

## Para usar:

Execute todas as células no Google Colab

Na última célula, substitua a URL pela imagem desejada

O sistema mostrará a imagem original + 5 similares

## Principais vantagens:

Não depende de metadados textuais

Considera características visuais (cores, texturas, formas)

Escalável com Annoy para grandes datasets

Fácil integração com pipelines de e-commerce

## Nota: Para produção, você precisaria:

Usar um dataset maior de produtos reais

Implementar armazenamento persistente dos embeddings

Adicionar tratamento de erros

Otimizar o pré-processamento

Implementar cache para consultas frequentes
