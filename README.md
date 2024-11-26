
# SPIKE-AI

O SPIKE é um protótipo de uma inteligência artificial que foi desenvolvida para a realização de uma atividade em minha graduação na faculdade de Análise e Desenvolvimento de Sistemas.
Seu objetivo, é ser um chatbot interativo com o objetivo de tirar duvidas de desenvolvedores e auxilia-los no desenvolvimento de tarefas como debugging ou criação de códigos. 

Além disso, uma funcionalidade unica do SPIKE é que além de ceder respostas ás perguntas dos usuarios, o spike tambem **Adiciona Links** de conteudos referentes á pergunta, caso o usuario queira aprofundar seu conhecimento no assunto.

Ele utiliza o modelo 3.2 do Llama com 1 Bilhão de parametros, versão essa que foi cedida pela plataforma Hugging Face. Além disso, conta com a utilização do sistema EXA Api para realizar as buscas de páginas na internet. É Obrigatório **possuir uma chave do Modelo do Llama 3.2 e do EXA**, para a utilização do sistema.

Segue link para o modelo: **https://huggingface.co/meta-llama/Llama-3.2-1B**
 
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

![image](https://github.com/user-attachments/assets/4c6d7ee7-ca7e-4140-9d1c-a8acf6e3f4cc)

## Rodando o Sistema

Uma vez que as chaves e o modelo estiver devidamente configurados, basta apenas rodar as caixas em ordem!

https://github.com/user-attachments/assets/9fb7c2f4-0f0a-437f-9958-20c0a4a11106

