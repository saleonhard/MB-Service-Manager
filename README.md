[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fsaleonhard%2FMB-Service-Manager&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

# MB Service Manager 🎛️


**MB Service Manager** é uma aplicação gráfica desenvolvida para facilitar o gerenciamento e monitoramento do Metabase sem a necessidade de utilizar Docker. A ferramenta oferece uma interface intuitiva, permitindo que usuários configurem, gerenciem e monitorem o serviço Metabase com facilidade, fornecendo feedback visual claro sobre o status do serviço.

## Funcionalidades ✨

- **Gerenciamento de Serviço:** Inicie e pare o serviço Metabase através de botões dedicados. 🚀🛑
- **Configuração de Banco de Dados:** Configure os parâmetros de conexão para MySQL ou H2. 🗃️
- **Monitoramento de Status:** Visualize o status atual do serviço com ícones e mensagens informativas na janela principal e na bandeja do sistema. 📈
- **Visualização de Logs:** Abra logs de serviço e erros para diagnóstico e solução de problemas. 📜🔍
- **Gerenciamento de Versões:** Adicione e selecione versões do Metabase conforme necessário. 📦
- **Inicialização Automática:** Configure o aplicativo para iniciar automaticamente com o sistema. ⚙️
- **Modo Oculto:** Minimize a aplicação para a bandeja do sistema, onde o status do serviço será indicado através de ícones de status. 🕵️‍♂️

 <p align="center">
  <img src="https://github.com/user-attachments/assets/bf88ccb2-d8c7-4733-9dca-f5d1dde3781c" alt="Captura de tela 2024-09-17 151940">
</p>


## Propósito do Projeto 🎯

O MB Service Manager foi desenvolvido para fornecer uma alternativa gráfica para o gerenciamento do Metabase sem a necessidade de Docker. A aplicação torna o processo de gerenciamento mais simples e direto, oferecendo um feedback visual claro sobre o estado do serviço, tanto na janela principal quanto na bandeja do sistema.

## Requisitos 📋

- **Java 8 ou superior:** O MB Service Manager requer o Java Runtime Environment (JRE) 1.8 ou superior para ser executado. Você pode baixar o Java em: [java.com](https://www.java.com/pt-BR/download/) ☕
- **Metabase:** Certifique-se de que o Metabase está configurado e pronto para ser gerenciado. 🛠️

## Como Usar 🛠️

O MB Service Manager está disponível como um arquivo Java Archive (.jar). Para executar o arquivo `.jar`, você precisa ter o Java Runtime Environment (JRE) 1.8 ou superior instalado em seu sistema.

1. **Baixe o Arquivo JAR da Versão Desejada:**
   - Visite [Metabase Releases](https://www.metabase.com/docs/latest/releases#metabase-open-source-edition-releases) e baixe o arquivo JAR da versão do Metabase que deseja utilizar.

2. **Executando o Arquivo .jar** 🎯
   - Você pode executar o arquivo `.jar` de duas maneiras:
     1. **Linha de Comando:** Execute o aplicativo a partir da linha de comando com o seguinte comando:
        ```bash
        java -jar caminho/para/MB Service Manager.jar
        ```
     2. **Clique Duplo:** Se o seu sistema estiver configurado para associar arquivos `.jar` com o Java Runtime, basta dar dois cliques no arquivo `.jar` para iniciar o MB Service Manager. 🖱️

## Funcionalidades Detalhadas 🛠️

1. **Configurar Parâmetros do Banco de Dados**

   - Preencha os campos de configuração do banco de dados, incluindo **Host**, **Porta**, **Database**, **Usuário**, e **Senha**.
   - Selecione o tipo de banco de dados (MySQL ou H2) e a versão desejada do Metabase. 🗂️

2. **Gerenciar o Serviço**

   - Clique em **Iniciar** para iniciar o serviço Metabase. 🚀
   - Clique em **Parar** para parar o serviço. 🛑
   - Utilize os botões para acessar logs de serviço e de erro. 📜

3. **Gerenciar Versões do Metabase** 📦

   - **Adicionar Versões:** Você pode adicionar novas versões do Metabase ao aplicativo para facilitar o gerenciamento e a troca entre versões. As versões devem seguir o formato **X.YY.Z** (exemplo: 0.45.0). 
   - **Selecionar Versões:** Escolha a versão desejada do Metabase para ser utilizada com o serviço. Isso é útil para testar diferentes versões ou realizar atualizações sem complicações.
   - **Visualizar Versões Disponíveis:** Na interface do MB Service Manager, você pode ver uma lista das versões instaladas e disponíveis para seleção. Isso ajuda a manter a organização e a clareza na escolha da versão correta.
     
     ![Captura de tela 2024-09-17 152926](https://github.com/user-attachments/assets/31969320-5da7-42bc-bd28-873c7503a90b)


4. **Configurar Inicialização Automática**

   - Marque a opção **Start Automatically** para que o serviço inicie automaticamente quando o sistema for iniciado. ⚙️

5. **Modo Oculto**

   - Minimize a aplicação para a bandeja do sistema. No modo oculto, o ícone da bandeja indicará o status atual do serviço com os seguintes ícones:
     - **Offline:** O serviço está parado. ⛔
     - **Online:** O serviço está ativo e funcionando corretamente. ✅
     - **Pendente:** O serviço está iniciando e ainda não está totalmente operacional. 🕑
     - **Erro:** O serviço encontrou um problema e pode não estar funcionando corretamente. ❌
    
     ![Captura de tela 2024-09-17 153007](https://github.com/user-attachments/assets/3467e63d-e72d-4b0b-a3bc-e96a04195094)


   O sistema indicativo de status também está disponível na janela principal do aplicativo, onde você pode ver o ícone e a mensagem correspondente ao status atual do serviço. 🖥️

## Contribua com o Projeto 🤝

Gostou do projeto? Quer colaborar? Entre em contato para discutir como você pode contribuir! Sua participação é muito bem-vinda e pode ajudar a tornar o MB Service Manager ainda melhor.

## Contato 📞

- **E-mail:** [sa.leonardo13@gmail.com](mailto:sa.leonardo13@gmail.com)
- **LinkedIn:** [linkedin.com/in/aquinoleonardo](https://linkedin.com/in/aquinoleonardo)
- **Twitter:** [@salenhard](https://twitter.com/saleonhard)

## Licença 📜

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
