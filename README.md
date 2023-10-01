# Repositório para Atividades de Machine Learning e Inteligência Artificial

## Sobre o projeto

Para cada módulo, é esperado que o membro consiga compreender o que foi feito e reproduzir com novos dados. Aqui, serão disponibilizadas bases de dados para que o membro consiga aplicar as técnicas aprendidas. Na pasta `data`, existe um notebook com uma breve descrição de cada base de dados e um script para download das mesmas. Faça download da base que deseja utilizar em sua análise (ou todas, caso queira) e utilize os notebooks disponível na pasta `notebooks` para realizar os exercícios de acordo com o módulo atual. Aqui é importante ressaltar que os notebooks de cada módulo servem como um guia, e não como uma receita de bolo. Muitas vezes dados diferentes exigirão abordagens diferentes, então é importante que o membro consiga compreender o que está sendo feito e adaptar para o seu caso. Aproveite esse espaço para tirar dúvidas e compartilhar suas análises com os demais membros.

## Repositório Oficial da Capacitação

Acesse o repositório oficial da capacitação [aqui](https://github.com/thomaschiari/ML_AI-Training).

## Uso e Instalação

Após clonar o repositório localmente, é necessário utilizar um ambiente virtual para facilitar a execução do projeto. 

### Utilizando `venv`:

1. Caso não tenha o `virtualenv` instalado, siga as instruções de instalação no site oficial: [Virtualenv](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/).

2. Rode o comando:
```
python3 -m venv env
```

3. Ative o ambiente virtual:
    - Windows:
    ```
    .\env\Scripts\activate.bat
    ```
    - Linux/MacOS:
    ```
    source env/bin/activate
    ```

4. Instale as dependências:
```
pip install -r requirements.txt
```

5. Para desativar o ambiente virtual, utilize o comando:
```
deactivate
```

### Utilizando `conda`:

1. Caso não tenha o `conda` instalado, siga as instruções de instalação no site oficial: [Conda](https://docs.conda.io/projects/miniconda/en/latest/).

2. Rode o comando:
```
conda env create -f environment.yml
```

3. Ative o ambiente virtual:
```
conda activate ml_ai-training
```

4. Para desativar o ambiente virtual, utilize o comando:
```
conda deactivate
```
