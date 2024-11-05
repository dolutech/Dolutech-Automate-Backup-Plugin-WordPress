# Dolutech Automate Backup

![License](https://img.shields.io/badge/license-GPL--2.0%2B-blue.svg)
![PHP Version](https://img.shields.io/badge/PHP-%3E%3D7.4-blue)
![WordPress Version](https://img.shields.io/badge/WordPress-%3E%3D6.5-blue)

O **Dolutech Automate Backup** é um plugin de backup completo para WordPress, oferecendo uma solução de backup e restauração prática e segura. Com suporte a armazenamento local e FTP, o plugin realiza backups de todo o ambiente do site e também permite restaurar os dados de forma completa e integrada, diretamente pelo painel do WordPress.

## Funcionalidades

- **Backup Completo:** Realiza backup completo dos arquivos do site e do banco de dados.
- **Armazenamento Local e FTP:** Armazene os backups localmente ou envie para um servidor FTP de sua escolha.
- **Agendamento de Backups:** Configure backups automáticos com frequências diárias, semanais, quinzenais ou mensais.
- **Restauração Completa:** Restaure seus arquivos e banco de dados diretamente pelo painel.
- **Logs Detalhados:** Acompanhe as operações realizadas com logs detalhados e uma barra de progresso.
- **Notificações por E-mail:** Receba notificações por e-mail sobre o status dos backups e restaurações.

## Requisitos

- **PHP:** 7.4 ou superior
- **WordPress:** 6.5 ou superior

## Instalação

1. **Faça o download** do repositório ou clone-o para o diretório `wp-content/plugins/`.
    ```bash
    git clone https://github.com/seu-usuario/dolutech-automate-backup.git
    ```
2. No painel do WordPress, vá até **Plugins > Plugins Instalados** e ative o **Dolutech Automate Backup**.
3. Acesse **Dolutech Backup** no menu do painel para configurar e iniciar seus backups.

## Configuração

1. Acesse **Dolutech Backup** no painel de administração do WordPress.
2. Defina o **Tipo de Backup** entre Local e FTP.
3. Para backups FTP, configure o endereço do servidor, usuário, senha e caminho de armazenamento.
4. Na seção de **Backup Automático**, defina a frequência e o horário desejado.
5. Insira um e-mail para **notificações automáticas** sobre o status dos backups.
6. Clique em **Salvar Configurações** para aplicar.

## Como Usar

### Fazer Backup Manual

1. Acesse **Dolutech Backup** no painel.
2. Clique em **Fazer Backup Manual** para iniciar um backup instantaneamente.
3. Acompanhe o progresso do backup na barra de progresso.

### Restaurar Backup

1. Na seção **Backups Locais Disponíveis**, selecione o backup desejado e clique em **Restaurar**.
2. Para restaurar usando um arquivo `.zip`, use a seção **Restaurar Backup por Upload**.

## Configurações do Plugin

| Configuração                | Descrição                                                                                      |
|-----------------------------|------------------------------------------------------------------------------------------------|
| **Tipo de Backup**          | Define o tipo de backup: Local ou FTP.                                                         |
| **Configurações de FTP**    | Insira servidor FTP, usuário, senha e caminho de backup no servidor FTP.                       |
| **Backup Automático**       | Ativa ou desativa backups automáticos.                                                         |
| **Frequência do Backup**    | Define a frequência do backup (diária, semanal, quinzenal, mensal).                           |
| **Horário do Backup**       | Define o horário do backup automático.                                                         |
| **Notificação por E-mail**  | Receba notificações automáticas sobre o status dos backups e restaurações.                    |

## Perguntas Frequentes

### Quais são os requisitos para usar este plugin?
- PHP 7.4 ou superior e WordPress 6.5 ou superior são necessários para utilizar este plugin.

### Onde são armazenados os backups?
- Você pode escolher entre armazenar backups localmente ou em um servidor FTP configurado nas opções do plugin.

### Como posso configurar as notificações por e-mail?
- No painel do plugin, insira um e-mail para receber atualizações sobre o status dos backups.

### Como configuro o agendamento automático de backups?
- Acesse a seção **Configurações de Backup Automático** e selecione a frequência e o horário desejado.

## Capturas de Tela

1. **Página de Configuração do Plugin**
   ![Página de Configuração](screenshot-1.png)

2. **Lista de Backups Disponíveis**
   ![Lista de Backups](screenshot-2.png)

3. **Configuração de Backup Automático**
   ![Configuração de Backup Automático](screenshot-3.png)

## Contribuição

Contribuições são bem-vindas! Para contribuir com o desenvolvimento:

1. Faça um fork do repositório.
2. Crie um novo branch para sua funcionalidade ou correção (`git checkout -b feature/nome-da-feature`).
3. Envie suas modificações com um pull request.

### Issues

Sinta-se à vontade para abrir uma [issue](https://github.com/seu-usuario/dolutech-automate-backup/issues) para reportar bugs, sugerir melhorias ou discutir novas funcionalidades.

## Changelog

### 0.1.0
- Lançamento inicial do plugin com funcionalidades de backup local e FTP, restauração, agendamento de backups automáticos e logs.

## Licença

Distribuído sob a licença GPL-2.0+. Consulte [LICENSE](http://www.gnu.org/licenses/gpl-2.0.txt) para mais informações.

## Suporte

Para dúvidas ou problemas, entre em contato através do e-mail: [suporte@dolutech.com](mailto:suporte@dolutech.com).

---

**Desenvolvido por Lucas Catão de Moraes** | [Dolutech](https://dolutech.com)

Se gostou do plugin, considere apoiar com uma doação!  
[Doe pelo PayPal](https://www.paypal.com/paypalme/cataodemoraes)
