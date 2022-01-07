# 💣 Auto BOMBCRYPTO

![GitHub repo size](https://img.shields.io/github/repo-size/victortp/auto-bombcrypto?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/victortp/auto-bombcrypto?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/victortp/auto-bombcrypto?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/victortp/auto-bombcrypto?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/victortp/auto-bombcrypto?style=for-the-badge)

<img src="https://github.com/victortp/auto-bombcrypto/blob/main/docs/logo.png" alt="Auto BOMBCRYPTO">

> Auto BOMBCRYPTO é uma ferramenta de automação para o jogo [Bombcrypto](https://app.bombcrypto.io/)

## 💎 Funcionalidades

- Realiza o login
- Seleciona os heróis para trabalhar (todos de uma vez/todos que estejam com a barra de energia verde)
- Atualiza a posição dos heróis no mapa
- Registra a quantidade de Bcoins do baú

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você possui a versão mais recente do `Python` instalada ([download](https://www.python.org/downloads/))
- Você sabe utilizar o `prompt de comando/terminal`
- Instalou o pacote `scrot` caso utilize sistema unix:

```
sudo apt install scrot
```

## 🚀 Instalando Auto BOMBCRYPTO

Para instalar o Auto BOMBCRYPTO, siga as etapas abaixo:

- Abra a pasta do projeto no prompt de comando/terminal

```
cd path/to/project-folder/
```

- Instale as dependências

```
pip install -r requirements.txt
```

## ☕ Usando Auto BOMBCRYPTO

Para usar o Auto BOMBCRYPTO, siga as etapas abaixo:

- Abra o [site do Bombcrypto](https://app.bombcrypto.io/)
- Abra a pasta do projeto no prompt de comando/terminal

```
cd caminho/para/pasta-do-projeto/
```

- Execute o projeto

```
python main.py
```

- Por ser uma ferramenta baseada em imagens, mantenha a janela do navegador visível em todos os momentos
- Para finalizar, basta apertar `ctrl + c` no prompt de comando/terminal

## ⚙️ Ajustes

Você pode alterar o comportamento da ferramenta alterando as variáveis abaixo no arquivo `main.py`:

> ⚠️ **Alterar essas variáreis pode quebrar a ferramenta**

```python
# TEMPO DE ESPERA DAS AÇÕES EM MINUTOS
SEND_HEROES_TO_WORK = 10 # Enviar heróis para o trabalho
REFRESH_HEROES_POSITION = 3 # Atualizar a posição dos heróis
LOG_BCOIN = 30 # Registrar os bcoins
CHECK_CONNECTION = 1/60 # Verificar a conexão

# DIVERSOS
SEND_ALL_HEROES_TO_WORK = False  # Enviar todos os heróis para o trabalho: True = sim | False = não
SAVE_LOG_TO_FILE = True  # Gravar o registro em arquivo: True = sim | False = não
RANDOMIZE_MOUSE_MOVEMENT = True  # Movimento do mouse aleatório: True = sim | False = não
```
