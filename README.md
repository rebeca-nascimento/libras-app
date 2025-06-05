📚 Aprendendo LIBRAS com Visão Computacional

Este projeto é um protótipo voltado ao ensino das vogais da Língua Brasileira de Sinais (LIBRAS), utilizando uma interface educativa baseada em técnicas de visão computacional e aprendizado de máquina, com suporte da biblioteca MediaPipe.

🔧 Tecnologias Utilizadas

- **Python 3.10+**
- **Streamlit** (interface web)
- **OpenCV** (leitura da webcam)
- **MediaPipe** (rastreamento das mãos)
- **KNN** (classificação dos gestos)
- **Scikit-learn** e **joblib** (modelagem e serialização)
- **NumPy**


📁 Estrutura do Projeto

libras-app/
├── main.py # Arquivo principal (página inicial - Streamlit)
├── assets/letras/ # Imagens das letras A, E, I, O, U que aparecem no site
├── model/
│ ├── modelo_libras_knn.pkl # Modelo treinado com KNN
│ ├── label_encoder.pkl # Codificação dos rótulos
│ ├── reconhecimentoA.py # Reconhecimento da letra A
│ ├── reconhecimentoAEIOU.py # Reconhecimento da sequência AEIOU
│ └── ...
├── pages/
│ ├── page2.py # Página da letra E
│ ├── page3.py # Página da letra I
│ └── ...
└── requirements.txt


🚀 Como Executar

1. Clone este repositório ou extraia o `.zip`
2. No terminal, acesse a pasta:
   ```bash
   cd libras-app
3. Instale as dependências:
	pip install -r requirements.txt
4. Execute a aplicação:
	streamlit run main.py


👩‍💻 Autoria

Projeto desenvolvido por Rebeca Oliveira e Ana Luiza Ribeiro 
Curso de Ciência de Dados – Fatec Rubens Lara.
