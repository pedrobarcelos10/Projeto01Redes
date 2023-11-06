# Aplicativo de Cliente de Email (Gmail) com Kivy

Este é um aplicativo simples de cliente de email construído com o framework Kivy, que permite enviar e receber emails usando servidor SMTP e o protocolo IMAP do Gmail. A seguir, fornecemos detalhes sobre as linguagens, dependências e como configurar o ambiente para rodar o aplicativo em sua máquina.

## Linguagens e Frameworks Utilizados

- **Python:** A linguagem de programação principal utilizada para desenvolver o aplicativo.
- **Kivy:** O framework Python usado para criar interfaces gráficas multiplataforma.

## Dependências

Para executar o aplicativo, você precisa instalar as seguintes dependências:

- **Kivy:** O Kivy é a principal dependência para criar a interface gráfica do aplicativo. Para instalá-lo, use o seguinte comando no terminal:

   ```bash
   pip install kivy
- **smtplib e imaplib:** Essas bibliotecas são usadas para enviar e receber emails. Elas são parte da biblioteca padrão do Python e não precisam ser instaladas separadamente.

## Como Instalar e Executar o Aplicativo

Siga estas etapas para configurar e executar o aplicativo:

1. **Clonar o Repositório:**
   Clone este repositório para sua máquina usando o comando git no seu terminal (É necessário ter o _Git SCM_ instalado):

   ```bash
   git clone https://github.com/pedrobarcelos10/Projeto01Redes.git

2. **Navegar para o Diretório:**
   Navegue para o diretório do aplicativo:

   ```bash
   cd nome-do-repositório

3. **Instalar as Dependências:**
   Instale as dependências necessárias conforme mencionado. (É necessário ter o Python instalado em seu sistema)

4. **Executar o Aplicativo:**
   Execute o aplicativo com o seguinte comando no terminal:

   ```bash
   python main.py

O aplicativo será iniciado e abrirá a tela de login.

5. **Uso do Aplicativo:**
   - Na tela de login, deverá ser inserido o endereço de email e senha do Gmail. Vale ressaltar que a senha deverá ser gerada nas configurações de sua conta para conseguir acessar seu email a partir de um aplicativo menos seguro.
   - Clique em _'Login'_ para acessar sua conta. Sendo bem sucedido o login, você será direcionado para a tela principal..
   - Na tela principal, para o envio do email, deverão ser preenchidos os campos _'De'_, _'Para'_, _'Assunto'_ e _'Corpo do email'_.
   - Ao preencher, clique no botão _'Enviar Email'_. Uma mensagem de sucesso será exibida e seu email será enviado.
   - Sua caixa de entrada também poderá ser visualizada clicando no botão _'Ver Caixa de Entrada'_.

**NÃO ESQUEÇA DE CONFIGURAR CORRETAMENTE A SENHA PARA O USO DE APLICATIVOS MENOS SEGUROS.**

No Gerenciamento de sua conta do Gmail, siga os passos:
- _Segurança_ > _Verificação em Duas Etapas_ > _Senhas de App_. Siga as instruções da página.

