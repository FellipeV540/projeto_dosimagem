## Caso de Uso: Controle de Acesso a Conteúdos Sensíveis

**Ator Principal:** Administrador do Sistema

**Pré-condições:**

-   O sistema da clínica de exames está em funcionamento.
-   Existem conteúdos sensíveis armazenados no sistema, como resultados de exames e históricos médicos dos pacientes.

**Fluxo Principal:**

1.  O administrador do sistema acessa o sistema interno da clínica de exames.
2.  O sistema exibe a tela de login.
3.  O administrador insere seu nome de usuário e senha nos campos correspondentes.
4.  O administrador clica no botão "Entrar" ou pressiona a tecla "Enter" para enviar as informações de login.
5.  O sistema verifica as credenciais do administrador e autentica o acesso.
6.  Após o login bem-sucedido, o administrador acessa o painel de controle do sistema.
7.  O administrador navega para a seção de configurações de segurança ou controle de acesso.
8.  O administrador define as políticas de acesso para os diferentes tipos de conteúdos sensíveis, especificando quais cargos ou departamentos têm permissão para visualizar ou modificar cada tipo de informação.
9.  O administrador salva as configurações de controle de acesso no sistema.
10.  Quando um usuário tenta acessar um conteúdo sensível, o sistema verifica suas credenciais e verifica se ele tem permissão para visualizar ou modificar esse conteúdo.
11.  Se o usuário estiver autorizado, o sistema concede acesso ao conteúdo solicitado.
12.  Se o usuário não estiver autorizado, o sistema exibe uma mensagem de erro informando que o acesso foi negado devido às restrições de segurança.

**Pós-condições:**

-   O sistema limita o acesso a conteúdos sensíveis apenas a pessoas autorizadas, de acordo com as políticas de controle de acesso definidas pelo administrador do sistema.

**Descrição:** Esse caso de uso garante que apenas pessoas autorizadas tenham acesso a conteúdos sensíveis, como informações médicas confidenciais, dentro do sistema da clínica de exames.



