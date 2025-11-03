# cdu12
Nome do Caso de Uso: Autenticar Usuário
Ator Primário: Usuário (ou Administrador, dependendo do sistema)
Descrição:
Permite que o usuário acesse o sistema informando suas credenciais (usuário e senha). O sistema valida as informações e concede acesso em caso de sucesso.

Fluxo Principal:

O caso de uso se inicia quando o usuário solicita o acesso ao sistema.

O sistema exibe a tela de login.

O usuário informa suas credenciais (usuário e senha).

O sistema valida as credenciais no banco de dados.

Se as credenciais forem válidas, o sistema concede o acesso e redireciona o usuário à tela inicial.

O caso de uso termina com o usuário autenticado.

Fluxos Alternativos:

A1 – Credenciais inválidas:

O sistema detecta que as credenciais não correspondem a um usuário válido.

O sistema exibe uma mensagem de erro.

O usuário pode tentar novamente.

Pré-condições:

O usuário deve estar previamente cadastrado.

Pós-condições:

O usuário autenticado tem acesso às funcionalidades do sistema de acordo com seu perfil.
