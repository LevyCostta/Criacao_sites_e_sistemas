# Python Dev: Criação de Sites e Sistemas com Python

Este repositório contém o código desenvolvido durante a aula 4 do curso "Python Dev: Criação de Sites e Sistemas com Python". O objetivo deste projeto é demonstrar os conceitos aprendidos e aplicar as técnicas de desenvolvimento web utilizando Python.

## Descrição do Projeto

O projeto "Hashzap" é um chat ao vivo desenvolvido em Python utilizando a biblioteca Flet. Este aplicativo permite que os usuários se conectem e conversem em tempo real de forma simples e intuitiva. A interface é projetada para ser amigável, com um fluxo de interação que guia o usuário desde a entrada no chat até o envio de mensagens.

### Funcionalidades

- **Interface Intuitiva**: O usuário inicia o chat clicando no botão "Iniciar Chat", que abre um diálogo para inserir seu nome.
- **Entrada no Chat**: Após inserir o nome e clicar em "Entrar no chat", o usuário é levado à interface principal do chat, onde pode enviar mensagens.
- **Envio de Mensagens**: O usuário pode digitar suas mensagens em um campo de texto e enviá-las clicando no botão "Enviar". As mensagens são exibidas em tempo real para todos os participantes do chat.
- **Comunicação em Tempo Real**: Utiliza WebSockets para permitir que as mensagens sejam enviadas e recebidas instantaneamente, criando uma experiência de chat fluida.

### Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para desenvolver o aplicativo.
- **Flet**: Biblioteca que permite a criação de interfaces gráficas de forma simples, integrando lógica de backend e frontend.
- **WebSockets**: Protocolo utilizado para comunicação em tempo real entre o cliente e o servidor.

### Estrutura do Código

O código é organizado em uma função principal que cria a interface do chat e gerencia a lógica de envio e recebimento de mensagens. Os principais componentes incluem:

- **Título e Botão de Início**: Um título "Hashzap" e um botão "Iniciar Chat" que inicia o fluxo de interação.
- **Diálogo de Boas-Vindas**: Um diálogo que solicita ao usuário que insira seu nome antes de entrar no chat.
- **Campo de Mensagem e Botão de Envio**: Um campo de texto para digitar mensagens e um botão para enviá-las.
- **Atualização em Tempo Real**: As mensagens enviadas são atualizadas na interface do chat em tempo real, permitindo que todos os usuários vejam as mensagens instantaneamente.

Este projeto é uma excelente oportunidade para aprender sobre desenvolvimento de aplicativos com Python e a implementação de funcionalidades de chat em tempo real utilizando a biblioteca Flet.

## Instalação

Para executar este projeto em sua máquina local, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/LevyCostta/Criacao_sites_e_sistemas.git
2. Navegue até o diretório do projeto:

 cd Criacao_sites_e_sistemas

3. Crie um ambiente virtual (opcional, mas recomendado):
   
 python -m venv venv
 source venv/bin/activate  # Para Linux/Mac
 venv\Scripts\activate  # Para Windows

4. Instale as dependências:
   
 pip install flet
