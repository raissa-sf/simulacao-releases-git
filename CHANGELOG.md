# Changelog

Todas as mudanças notáveis deste projeto serão documentadas neste arquivo.

## [1.0.0] - 2026-06-14

### Adicionado

* Página inicial para usuário operador (`pg002.html`).
* Página de mensagens/erro (`msg.html`).
* Validação do campo usuário na tela de login.
* Redirecionamento para a página do administrador quando o usuário informado for `admin`.
* Redirecionamento para a página do operador para qualquer outro usuário válido.

### Alterado

* Página de login (`index.html`) atualizada para implementar as regras de navegação do Release 5.3.
* Fluxo de autenticação ajustado para validar apenas o campo usuário.
* Página inicial do administrador (`pg001.html`) integrada ao novo fluxo de navegação.

### Release

* Conclusão do Release 5.3.

## [0.2.0] - 2026-06-11

### Adicionado

* Página inicial do administrador (`pg001.html`).
* Navegação da página de login para a página do administrador.

### Alterado

* Página de login (`index.html`) atualizada para direcionar o usuário à página do administrador.
* Tela de login mantida sem validação dos campos de usuário e senha, conforme especificação do Release 5.2.

### Release

* Conclusão do Release 5.2.

## [0.1.0] - 2026-06-09

### Adicionado

* Estrutura inicial do projeto.
* Página de login (`index.html`).
* Página de aviso (`working.html`).
* Funcionalidade de redirecionamento para a página de aviso ao clicar no botão da tela de login.
* Mensagem "Em construção" implementada conforme especificação do Release 5.1.

### Corrigido

* Ajustes iniciais de versionamento e organização do repositório Git.

### Release

* Conclusão do Release 5.1.
