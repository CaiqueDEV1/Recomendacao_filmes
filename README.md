# Sistema de Recomendação de Filmes 🎬
Este projeto implementa um sistema de recomendação de filmes usando dados de avaliação de usuários e metadados de filmes. O sistema é baseado em filtragem colaborativa, onde a avaliação de um filme por um usuário é usada para prever e recomendar filmes para outros usuários com interesses semelhantes.

## 📋 Pré-requisitos
Para rodar este projeto, você precisa de:

- Python 3.x
- Pandas
- NumPy

## ⚙️ Instalação
Clone o repositório e instale as dependências:
``git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
pip install -r requirements.txt``

## 🚀 Uso
- Carregue os dados: O notebook carrega os dados dos arquivos ``movies_metadata.csv`` e ``ratings.csv.``
  - **Os dois datasets são grandes, então aqui está o link para baixa-los:**
  - https://drive.usercontent.google.com/download?id=19tLCliDpoAlQNt84dnUZDsHF_yRfJ3AE&export=download&authuser=0
- Pré-processamento dos dados: Filtra e ajusta os dados para remoção de valores nulos e renomeação de colunas.
- Execução do modelo de recomendação: Rode as células do notebook para processar as recomendações.

### Para executar o projeto, abra o Jupyter Notebook e execute as células sequencialmente.
``jupyter notebook ProjetoRecomendacao.ipynb``

## 🛠️ Detalhes Técnicos
- Filtragem Colaborativa: Utiliza a matriz de avaliações de filmes por usuários para encontrar similaridades.
- Bibliotecas: O projeto utiliza pandas para manipulação de dados e numpy para operações numéricas.

## 🤝 Contribuição
Sinta-se à vontade para abrir um "Pull Request" para sugestões de melhorias ou novos recursos.
