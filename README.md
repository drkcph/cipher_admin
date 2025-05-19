# cipher_admin

Central de Informações, Guias e Documentações do Sistema

---

**cipher_admin** é um painel administrativo premium para FiveM, desenvolvido para simplificar a gestão completa do seu servidor. Com funcionalidades robustas para controle de jogadores, permissões customizáveis, comandos administrativos e monitoramento em tempo real, o cipher_admin é a solução ideal para administradores que buscam eficiência, segurança e praticidade.

> **ATENÇÃO:** Este é um script pago. Para adquirir sua licença oficial, visite nosso site:  
> [https://cphlab.xyz/cipher_admin](https://cphlab.xyz/cipher_admin)

Antes de iniciar a instalação, certifique-se de que seu ambiente atende aos seguintes pré-requisitos:

- Servidor FiveM com conexão estável  
- Banco de dados MySQL configurado e acessível  
- Node.js (versão recomendada: 22.15.1) para rodar o painel  
- Permissões administrativas no servidor para configurar recursos  

Siga o passo a passo para configurar o cipher_admin no seu servidor FiveM:

1. Faça o download do script adquirido no nosso site oficial ou, caso já possua sua licença, acesse: [DOWNLOAD DO SCRIPT](https://download.cphlab.xyz/cph_admin)

    ```bash
    https://download.cphlab.xyz/cph_admin
    ```

2. Copie o arquivo compactado `cipher_admin.rar` para dentro da pasta `resources` ou `[cipherlab]` do seu servidor FiveM.

3. Extraia o arquivo `cipher_admin.rar` para obter a pasta `cipher_admin` dentro da pasta `resources` ou `[cipherlab]`.

4. Abra o arquivo de configuração (`config.lua`) e ajuste as informações conforme as necessidades do seu servidor. Verifique se o banco de dados está criado e se o usuário possui as permissões adequadas.

5. No arquivo principal do seu servidor (`server.cfg` ou equivalente), adicione a seguinte linha para garantir que o recurso seja iniciado:

    ```
    ensure cipher_admin
    ```

No arquivo `config.lua` você pode personalizar:

- Definição dos níveis e permissões dos administradores  
- Tempo e tipo de punições (kick, ban, mute) para cada ação  
- Configurações de logs, notificações e integrações externas  

---

### Comando Principal

|ㅤㅤㅤ ㅤ  ㅤㅤComandoㅤㅤㅤ   ㅤㅤㅤ|ㅤㅤㅤㅤ  ㅤ ㅤDescriçãoㅤ ㅤ  ㅤㅤㅤㅤ|ㅤㅤㅤㅤ ㅤ  ㅤPermissão necessáriaㅤㅤㅤ ㅤ  ㅤㅤ|
|------------|----------------------|---------------------|
| `/cadmin`  | Abre o painel        | admin.perm          |

### Atalho Principal

|ㅤㅤㅤㅤㅤㅤㅤTeclaㅤㅤㅤㅤㅤㅤㅤ|ㅤㅤㅤㅤㅤㅤㅤDescriçãoㅤㅤㅤㅤㅤㅤㅤ|ㅤㅤㅤㅤㅤㅤPermissão necessáriaㅤㅤㅤㅤㅤㅤㅤ|
|-------|-----------------|---------------------|
| `F2`  | Abre o painel   | admin.perm          |

Para utilizar o painel administrativo:

- Execute o comando ou pressione a tecla de atalho no servidor  
- Faça login com suas credenciais administrativas  
- Gerencie jogadores, revise logs e ajuste permissões com facilidade  

---

## Suporte e Atualizações

Como este é um produto pago com suporte dedicado, para dúvidas, atualizações e suporte técnico, acesse nosso Discord:  
[https://cphlab.xyz/discord](https://cphlab.xyz/discord)

Você também pode abrir issues no repositório para reportar bugs ou solicitar melhorias.

---

**Importante:** Este script é fornecido sob licença. Sua distribuição não autorizada é proibida. Utilize sempre versões oficiais adquiridas em nosso site.

---

> Desenvolvido e mantido por **CipherLab™**  
> [https://cphlab.xyz](https://cphlab.xyz)
