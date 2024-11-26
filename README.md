
# SPIKE-AI

O SPIKE é um protótipo de uma inteligência artificial que foi desenvolvida para a realização de uma atividade em minha graduação na faculdade de Análise e Desenvolvimento de Sistemas.


## Autores

- [@Leonardo Paschoa Braga](https://www.github.com/LeonardoPaschoaBraga16)
- [@Matheus Silva Gomes](https://www.github.com/MatheusSilvaGomes07)
- [@Vitória Santos](https://www.github.com/VitoriaSantosd)
- [@Felipe Thaylan Pereira](https://www.github.com/ThaylanFe)
- [@Kauã Oliveira de Souza](https://www.github.com/kau-a)


## Documentação das Bibliotecas

#### Bibliotecas
O sistema foi configurado para rodar no google colab, tendo junto consigo as principais bibliotecas

```http
!pip install exa_py transformers torch accelerate bitsandbytes huggingface_hub
!pip install --upgrade gradio
```

#### Chaves

Dentro do sistema, tambem foram configuradas duas chaves principais. Uma sendo para o modelo Llama 3.2 no Hugging Face, e outra apra o uso da EXA API.

Segue Links: https://huggingface.co; https://exa.ai


| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `TOKEN` | `string` | **Obrigatório**. A chave do Hugging Face |
| `EXA_KEY` | `string` | **Obrigatório**. A chave do EXA |

As chaves deverão ser colocadas no campo "Secrets" do Google Colab, para assim então, permitir o acesso a plataforma




## Rodando o Sistema

Uma vez que as chaves e o modelo estiver devidamente configurados, basta apenas rodar as caixas em ordem!

