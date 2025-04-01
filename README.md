# Projeto de Reconhecimento de Texto

Este projeto visa utilizar Inteligência Artificial para realizar o reconhecimento de texto em imagens utilizando OCR (Reconhecimento Óptico de Caracteres). Durante o processo, explorei o uso de ferramentas de IA como o Azure OpenAI e bibliotecas de OCR em Python.

## Estrutura do Repositório

- **inputs/**: Contém as imagens que foram usadas para o reconhecimento de texto.
- **output/**: Contém os resultados de reconhecimento de texto extraídos das imagens.

## Processo

1. Selecionei imagens contendo textos para testar o reconhecimento.
2. Utilizei a ferramenta Azure OCR para realizar a extração de texto das imagens.
3. Salvei os resultados de texto extraído em arquivos `.txt` na pasta `output`.

## Imagens Processadas

### Imagem 1: 
![Imagem 1](inputs/imagem1.png)
**Texto extraído**:  
[conteúdo do arquivo output/resultado_imagem1.txt]

### Imagem 2: 
![Imagem 2](inputs/imagem2.png)
**Texto extraído**:  
[conteúdo do arquivo output/resultado_imagem2.txt]

## Insights

- O reconhecimento de texto pode ser altamente preciso dependendo da qualidade da imagem e da clareza do texto.
- As ferramentas de IA, como o Azure OCR, são muito úteis para extrair texto de documentos escaneados ou imagens com textos.
- É importante realizar uma pré-processamento nas imagens, como aumentar o contraste e reduzir ruídos, para obter melhores resultados.

## Possibilidades Futuras

- Melhorar a precisão do OCR em imagens com baixa resolução.
- Integrar o sistema de OCR com ferramentas de automação de workflows, como chatbots ou assistentes virtuais.
