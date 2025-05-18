# Seu Guia de Estudos Personalizado com Google Gemini

## Descrição do Projeto

Este projeto consiste em um chatbot desenvolvido em Python, utilizando a API do Google Gemini, com o objetivo de gerar planos de estudos personalizados para estudantes. Ao interagir com o chatbot, o usuário informa seu estilo de aprendizado, horários disponíveis, matérias prioritárias, tempo de estudo desejado e objetivos. Com base nessas informações, o chatbot gera um plano de estudos semanal detalhado, incluindo sugestões de recursos de aprendizado online e dicas de técnicas de estudo adequadas ao perfil do usuário.

## Funcionalidades

* Coleta de informações do usuário: Pergunta sobre estilo de aprendizado, horários, matérias, tempo de estudo e objetivos.
* Geração de plano de estudos: Cria um plano semanal com horários dedicados a cada matéria.
* Sugestão de recursos de aprendizado: Recomenda links e materiais online relevantes para o estilo de aprendizado e as matérias prioritárias.
* Dicas de técnicas de estudo: Oferece conselhos sobre métodos de estudo eficazes para o perfil do estudante.
* Formatação em Markdown: Apresenta o plano de estudos de forma clara e organizada usando a sintaxe Markdown.

## Como Usar

1.  Acesse o código: O código principal do chatbot está no arquivo `Projeto Imersão 2025.ipynb`.
2.  Abra no Google Colab: Recomenda-se executar este projeto no Google Colab (colab.research.google.com).
3.  Obtenha uma chave de API do Google Gemini: Acesse (https://makersuite.google.com/app/apikey) e crie uma nova chave de API.
4.  Configure a chave de API: No código do Colab, localize a linha que define a variável de ambiente `GOOGLE_API_KEY` e substitua `"SUA_CHAVE_DE_API"` pela sua chave real.
5.  Execute o código: Execute a célula de código que contém todo o script Python. O chatbot iniciará a interação, fazendo perguntas sobre suas necessidades de estudo.
6.  Responda às perguntas: Forneça as informações solicitadas.
7.  Visualize o plano de estudos: Após responder a todas as perguntas, o chatbot exibirá o seu plano de estudos personalizado formatado em Markdown.

## Tecnologias Utilizadas

* Python
* Google AI Python Library (`google-generativeai`)
* Google Gemini API
* Google Colab (ambiente de desenvolvimento)

## Desafios e Lições Aprendidas

Durante o desenvolvimento deste projeto, enfrentei o desafio de encontrar um modelo da API do Google Gemini que fosse compatível com a função de geração de conteúdo (`generateContent`). Inicialmente, tentei usar o modelo `gemini-pro`, mas encontrei erros de modelo não encontrado ou deprecado. Após explorar os modelos disponíveis (listados através da função `genai.list_models()`), consegui implementar o chatbot utilizando o modelo final.

Essa experiência me ensinou a importância de verificar a documentação da API e a disponibilidade dos modelos, além de ser flexível na escolha da ferramenta para alcançar o objetivo do projeto.

## Autora

Giovanna Benazzi de Araujo.
