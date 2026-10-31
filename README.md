# Nullbanker Sender

![Status](https://img.shields.io/badge/status-active-success.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-1.0.0-black.svg)

O **Nullbanker Sender** é a plataforma oficial da **Nullbanker** para envio de e-mails em massa via SMTP. Com uma interface desktop moderna, ele permite importar listas de contatos, editar templates HTML em tempo real e gerenciar todo o processo de disparo com controle total.

---

## AVISOS IMPORTANTES (Leia antes de usar)

1. **Falso Positivo de Antivírus:** O executável foi gerado com PyInstaller. É **normal** que o Windows Defender ou o Chrome exibam um alerta dizendo *"O Windows protegeu o seu PC"*. Para executar, clique em **"Mais informações"** e depois em **"Executar assim mesmo"**.
2. **Uso Responsável:** Esta ferramenta é destinada ao envio de e-mails **transacionais** e legítimos (para contatos que consentiram com o recebimento). O uso para **spam** é estritamente proibido e viola os Termos de Serviço do Gmail e a legislação brasileira (Marco Civil da Internet).
3. **Limite do Gmail:** Contas gratuitas do Gmail têm um limite de aproximadamente **500 e-mails por dia**. Não exceda esse limite para evitar o bloqueio da conta.
4. **Segurança:** A senha do seu e-mail SMTP fica salva apenas na memória do aplicativo durante a execução. Não compartilhe o `.exe` com terceiros se ele estiver configurado com suas credenciais.

---

## Funcionalidades

- **Interface SaaS Moderna:** Tema Dark Mode com paleta profissional.
- **Autenticação de Acesso:** Login restrito a operadores autorizados.
- **Editor de HTML Integrado:** Personalize o e-mail com a tag `{{nome}}`.
- **Importação de CSV:** Leitura rápida de listas de contatos.
- **Configuração SMTP Dinâmica:** Altere servidor, porta e credenciais pela interface.
- **Controle de Disparo:** Botões de Iniciar/Parar, barra de progresso e console de logs.

---

## Tutorial de Instalação (Para Usuários Finais)

### Opção 1: Baixar o Executável (Recomendado para Windows)

1. Vá até a aba **[Releases](https://github.com/KAKABANKER/nullbankersender/releases)** deste repositório.
2. Na versão mais recente, clique em **`Nullbanker.exe`** para baixar.
3. Quando o download terminar, **clique com o botão direito** no arquivo e selecione **"Propriedades"**.
4. Na parte inferior, marque a caixa **"Desbloquear"** e clique em **"Aplicar"**. (Isso evita bloqueios do Windows).
5. Dê **dois cliques** no arquivo para abrir o aplicativo.
6. Na tela de login, insira o usuário e senha fornecidos pela equipe Nullbanker.

### Opção 2: Executar via Código-Fonte (Para Desenvolvedores)

1. Clone o repositório:
   ```bash
   git clone https://github.com/KAKABANKER/nullbankersender.git
   cd nullbanker
