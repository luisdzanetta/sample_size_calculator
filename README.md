# Calculadora de Mínimo Efeito Detectável (MDE)

## Descrição

Este aplicativo calcula o Efeito Mínimo Detectável (MDE) para testes de taxa de conversão com base no nível de significância estatística e poder, número de semanas no experimento, taxa de conversão do controle, tamanho da amostra por semana e número de variantes. Caso você tenha alguma dúvida sobre como o cálculo foi feito, visite a página **'Cálculo'**. Para saber mais sobre os conceitos utilizados nesse app, visite a página **'Conceitos e Definições'**.

## Funcionalidades

- **Calculadora de MDE**: Permite calcular o MDE com base em parâmetros específicos.
- **Visualização Gráfica**: Gera gráficos interativos para visualização do MDE ao longo das semanas.

## Tecnologias Utilizadas

- **Python**
- **Pandas**
- **Matplotlib**
- **Streamlit**
- **Bokeh**

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd seu-repositorio
    ```
3. Crie um ambiente virtual:
    ```bash
    python -m venv venv
    ```
4. Ative o ambiente virtual:
    - Para Windows:
        ```bash
        venv\Scripts\activate
        ```
    - Para macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

## Como Usar

1. Execute o aplicativo:
    ```bash
    streamlit run app.py
    ```
2. Abra o navegador e navegue até:
    ```
    http://localhost:8501
    ```

## Estrutura do Projeto

```plaintext
.
├── app.py
├── requirements.txt
└── README.md
