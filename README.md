# festival

Descreva aqui as alterações/correções que fez

O atributo de ordenar na classe meta define como os dados são organizados nas consultas e nas views a listagem foi ajustada para seguir a ordem da data de forma crescente. No modelo do concerto a configuração de ordenação permite que o sistema organize os eventos primeiro pelo dia e depois pelo horário para que o cartaz do festival seja apresentado cronologicamente. 

 O formulário de edição dos concertos foi atualizado para incluir todos os campos disponíveis o que permite ao administrador alterar qualquer detalhe da banda ou do palco associado e não apenas o horário como acontecia antes. Foi também adicionado um botão para apagar concertos que funciona através de um formulário seguro e uma função na lógica do servidor que elimina o registo e devolve o utilizador à lista principal. 
 
 A funcionalidade de criar novos concertos foi totalmente implementada através de uma nova rota e de um formulário que permite escolher as bandas existentes para os novos horários. Para os palcos foi criado um novo campo de acessibilidade que guarda se o local está preparado para mobilidade reduzida e a página agora exibe a capacidade total de pessoas e a contagem automática de quantos concertos estão agendados para cada espaço.
  
    A edição de palcos foi ativada com um formulário próprio que permite atualizar o nome e a imagem de cada local garantindo que o servidor processa corretamente os ficheiros enviados.
    
    O aspeto visual foi melhorado para que o cabeçalho do palco permita aceder à edição ao passar o rato mantendo a consistência com outras partes do site e agora cada palco exibe a lista dos seus concertos em blocos individuais por baixo da fotografia