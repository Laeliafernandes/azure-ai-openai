# Exemplo de uso do Azure AI Vision e Vision Studio.

Este repositório é uma breve descrição sobre o Visio Studio do Azure.

O Vision Studio é uma solução do Azure que simplifica o desenvolvimento e a integração de soluções de visão computacional, permitindo construir e integrar funcionalidades do Azure AI Vision sem a necessidade de escrever código. 

Exemplo de uso: Extração de texto de uma imagem (OCR)

Input: Uma imagem contendo texto impresso ou manuscrito, como uma foto de uma placa ou um documento escaneado.

Processo: Utilizando a funcionalidade de OCR do Vision Studio, a imagem é processada para identificar e extrair o texto presente.

Output: O texto extraído é retornado em formato de texto editável. Por exemplo, ao processar uma imagem de uma placa com a inscrição "Rua do Sol, 23", o output seria:

```
Rua do Sol, 23
```

# Alguns insights

Em  relação a um sistema RAG tradicional o Azure Vision Studio adiciona um novo nível de entrada de dados ao permitir que o modelo de IA recupere informações de imagens, documentos escaneados, placas, notas manuscritas e etc.
