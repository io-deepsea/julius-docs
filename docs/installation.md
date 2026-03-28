# **Instalação e Configuração**

Existem duas formas de utilizar o **Julius**: adicionando o bot oficial ao seu servidor ou rodando a sua própria instância do código fonte.

## 1. Adicionando ao seu Servidor (Rápido)
Se você não quer lidar com código e só quer começar a economizar, use o link oficial de convite:

* [Convite do Julius Bot](https://discord.com/api/oauth2/authorize?client_id=SEU_ID_AQUI&permissions=8&scope=bot)

> **Nota:** Certifique-se de ter permissão de "Gerenciar Servidor" para adicionar o bot.

---

## 2. Rodando Localmente (Para Desenvolvedores)
Se você quer contribuir ou rodar sua própria versão, siga os passos abaixo. O Julius foi desenvolvido e testado em ambiente **Linux**.

### Pré-requisitos
* **Java 17** ou superior.
* **Maven** (para gerenciar dependências).
* **Token do Discord:** Crie uma aplicação no [Discord Developer Portal](https://discord.com/developers/applications) e gere um Token de Bot.

### Passo a Passo

1. **Clone o repositório:**
    
    ```
    git clone [https://github.com/io-deepsea/julius.git](https://github.com/io-deepsea/julius.git)
    && cd julius
    ```