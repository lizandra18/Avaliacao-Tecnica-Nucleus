**Relatório de Testes** 

- **Identificador Único/Versão** <br>
   #1

- **Resumo dos Testes Realizados** <br>
   Criação de Conta <br>
   Login <br>
   Editar dados pessoais: nome da conta <br>
   Editar dados pessoais: número de telefone <br>
   Navegar pela aplicação aleátoriamente, observando menus e botões <br>
   Buscar produtos <br>

- **Caso de Teste** <br>
    #1 

- **Título** <br>
   **C** - Campos Obrigatórios <br>
    Verificar o comportamento da aplicação ao deixar de preencher campos obrigatórios

- **Contexto** <br>
   Estava usando o Chrome Version 105.0.5195.127
   Sistema Operacional: Windows 11

- **Resultado** <br>
    A aplicação apresentou os resultados esperados em todos os testes <br>

---
- **Caso de Teste** <br>
    #2 

- **Título** <br>
   **U** - Usabilidade dos menus <br>
    Verificar o comportamento dos botões e menus da aplicação

- **Contexto** <br>
   Estava usando o Chrome Version 105.0.5195.127
   Sistema Operacional: Windows 11

- **Resultado** <br>
    A aplicação apresentou os resultados esperados em todos os testes <br>

---
- **Caso de Teste** <br>
    #3 

- **Título** <br>
   **E** - Estouro de Campos <br>
    Verificar o comportamento da aplicação ao inserir nos campos uma grande quantidade de caracteres

- **Contexto** <br>
   Estava usando o Chrome Version 105.0.5195.127
   Sistema Operacional: Windows 11

- **Resultado** <br>
    Ocorreram dois incidentes <br>

- **Descrição do Incidente #1** <br>
    Após seguir o passo a passo a seguir, a aplicação se comportou de maneira incorreta, revelando assim o incidente: <br>

    1. Abri o Chrome <br>
    2. Acessei a página [Fla Barcelos Art](https://www.flabarcellosart.com.br/) <br>
    3. Iniciei a sessão <br>
    4. Cliquei em 'Minha Conta' <br>
    5. Cliquei em 'Editar' dados pessoais <br>
    6. Digitei no campo 'Nome Completo' uma grande quantidade de caracteres (2000) e deixei os outros campos em branco <br>
    7. Cliquei em 'Salvar Alterações' <br>
    8. A tela "quebra" e mostra a mensagem 'Erro-404' <br><br> 

- **Evidências** <br>
    Screenshot (erro404.png) <br>

- **Severidade** <br>
    Baixa <br>

- **Prioridade** <br>
    Baixa <br>

---
- **Descrição do Incidente #2** <br>
    Após seguir o passo a passo a seguir, a aplicação se comportou de maneira incorreta, revelando assim o incidente: <br>

    1. Abri o Chrome <br>
    2. Acessei a página [Fla Barcelos Art](https://www.flabarcellosart.com.br/) <br>
    3. Iniciei a sessão <br>
    4. Cliquei em 'Minha Conta' <br>
    5. Cliquei em 'Editar' dados pessoais <br>
    6. Digitei no campo 'Telefone(opcional)' uma determinada quantidade de caracteres (51) e deixei os outros campos com os dados originais da conta <br>
    7. Cliquei em 'Salvar Alterações' <br>
    8. Fui redirecionada a uma página com a seguinte mensagem: "Estamos resolvendo um problema no servidor. Por favor, tente novamente em alguns minutos" <br>
    9. Ao atualizar a página ela continuou do mesmo jeito, mas ao clicar em voltar para a pagina anterior ela volta para a pagina de edição de dados <br><br>

- **Evidências** <br>
    Screenshot (problemaNoServidor.png) <br>

- **Severidade** <br>
    Baixa <br>

- **Prioridade** <br>
    Baixa <br>

---
- **Outros incidentes** <br>
    Incidentes ocorridos antes, durante ou depois dos testes mas que não foram guiados pela heurísticas e sim pela experiencia do usuário <br>
- **Descrição** <br>
    1 - Problemas na responsividade da aplicação <br>

    Após seguir o passo a passo a seguir, a aplicação se comportou de maneira incorreta, revelando assim o incidente: <br>

    1. Ao redirecionar a aplicação, em determinado momento, o elemento de usuário sobrepoem o de atendimento com os nomes ficando em cima do outro <br><br>

- **Evidências** <br>
    Screenshot (bugResponsividade.png) <br>

- **Severidade** <br>
    Baixa <br>

- **Prioridade** <br>
    Baixa <br>
---
- **Descrição** <br>
    2 - O campo de quantidade de produtos a serem comprados, permite uma grande quantidade de números <br>

    Após seguir o passo a passo a seguir, a aplicação se comportou de maneira incorreta, revelando assim o incidente: <br>

    1. Adicionei uma grande quantidade de número no campo de quantidade de produtos <br>
    2. Consegui adicionar adicionar no carrinho <br>
    3. Ao clicar em Finalizar compra, ele redireciona para a página de dados de entrega
    4. Ao tentar definir os dados da entrega ele retorna uma mensagem de erro: "Não há opções de envio para este endereço"

- **Evidências** <br>
    Screenshot (quantidadeDeProdutos.png, quantidadeDeProdutos.png) <br>

- **Severidade** <br>
    Baixa <br>

- **Prioridade** <br>
    Baixa <br>