-----

# Flappy Bird com Pygame ✨

Bem-vindo ao projeto de recriação do clássico jogo **Flappy Bird**, desenvolvido em Python com a biblioteca **Pygame**. Este é um projeto simples, mas que demonstra conceitos importantes de programação orientada a objetos, modularização de código e gerenciamento de recursos, tudo em um ambiente de desenvolvimento limpo e profissional.

Prepare-se para desafiar-se a voar entre os canos e a superar sua pontuação máxima\! 🐦

-----

## 🚀 Guia de Configuração e Execução

Este guia irá guiá-lo por todas as etapas necessárias para que o jogo rode perfeitamente em sua máquina, desde a configuração inicial até a execução final.

### 1\. Requisitos do Sistema

Antes de começar, certifique-se de que a linguagem Python está instalada em seu computador. Este projeto é compatível com o **Python 3.8** e versões superiores. Você pode verificar a sua versão abrindo o terminal e executando o comando:

```bash
python --version
# Ou, em alguns sistemas:
python3 --version
```

### 2\. Estrutura do Projeto

Para que o código funcione corretamente, é essencial que a estrutura de pastas e arquivos esteja organizada. As importações e os caminhos para os recursos de imagem e som dependem dessa organização.

Crie as pastas e coloque os arquivos conforme a estrutura abaixo, na pasta principal do seu projeto:

```
/seu_projeto/
├── main.py
├── jogo.py
├── atores.py
├── constantes.py
├── requirements.txt
├── .gitignore (opcional, mas recomendado)
├── imgs/
│   ├── bg.png
│   ├── base.png
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   └── pipe.png
└── sounds/
    ├── gameover.ogg
    └── overflow.ogg
```

-----

## 3\. Configuração Profissional com Ambiente Virtual

O uso de um **ambiente virtual** é a melhor prática em projetos Python. Ele cria um ambiente isolado para as dependências do seu projeto, evitando conflitos com outras bibliotecas instaladas em seu sistema global. Em poucas palavras, você garante que as bibliotecas do seu jogo não causem problemas em outros projetos.

### Passo 1: Criando o Ambiente Virtual

Abra o terminal ou prompt de comando na pasta do seu projeto. O comando a seguir criará a pasta `.venv` que abrigará o ambiente virtual.

```bash
# Para Linux ou macOS, use python3
python3 -m venv .venv

# Para Windows, use python
python -m venv .venv
```

### Passo 2: Ativando o Ambiente

Após a criação, você deve ativar o ambiente virtual. Isso faz com que o terminal utilize as bibliotecas instaladas dentro da pasta `.venv` em vez de usar as bibliotecas globais do seu sistema. O comando é diferente para cada sistema operacional:

**No Windows:**

```bash
.venv\Scripts\activate
```

**No Linux ou macOS:**

```bash
source .venv/bin/activate
```

Uma vez ativado, você verá `(.venv)` no início da linha de comando, indicando que o ambiente está pronto para uso.

### Passo 3: Instalando as Dependências

A única dependência necessária para este projeto é a biblioteca Pygame. O arquivo `requirements.txt` serve para listar todas as dependências do projeto, facilitando a instalação.

Crie um arquivo chamado **`requirements.txt`** com o seguinte conteúdo simples:

```txt
pygame
```

Com o ambiente virtual ativado, instale as dependências com o comando:

```bash
pip install -r requirements.txt
```

-----

## 4\. Prontos para Jogar\! 🎮

Com todas as dependências instaladas no ambiente virtual, você pode finalmente executar o jogo.

Certifique-se de que o ambiente virtual está ativado e que você está no diretório principal do projeto. Em seguida, execute o arquivo `main.py` com o comando apropriado para o seu sistema:

```bash
# Para Windows
python main.py

# Para Linux ou macOS
python3 main.py
```

O jogo Flappy Bird será iniciado em uma nova janela. Use a **barra de espaço** para fazer o pássaro pular e desvie dos canos\!

Divirta-se\! 🚀