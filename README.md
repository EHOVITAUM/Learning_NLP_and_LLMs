# Learning_NLP_and_LLMs

Você sabe o que são LLM´S e Embeddings ?
Já ouviu falar de bancos de dados vetoriais?
Large Language Models(LLM) são algoritmos de aprendizado de máquina que processam e geram texto.
São treinados para entender e gerar linguagem humana, um algoritmo muito conhecido é o ChatGPT da OpenAI, mas existem outros como o Google Bert, o LLaMa do Facebook e muitos outros.



Embeddings são representações matemáticas de coisas do mundo real.
É um vetor(lista) de valores que o algoritmo usa para representar dados 
não estruturados como: fotos , videos, audios e textos. Figura 2.

Os Embeddings são organizados em um espaço semântico, onde palavras ou conceitos semanticamente similares estão próximos no espaço vetorial. Isso significa que palavras com significados semelhantes terão representações vetoriais mais próximas entre si.
Os Emebeddings possuem milhares de dimensões, no exemplo abaixo vemos apenas duas dimensões por questões didáticas, mas é possível ver que pessoas mais velhas do gênero masculino estão próximas no espaço vetorial, enquanto crianças e mulheres estão mais distantes. Figura 3. 

Bancos de dados vetoriais são bancos criados para armazenar esse tipo de dado, onde temos o índice dos dados, os Embeddings e seus metadados que tem a função de descrever as características e propriedades dos vetores armazenados, eles nos mostram o texto que esta armazenado.(temos o Chroma e o Pinecone como os mais conhecidos) Figura 4.

