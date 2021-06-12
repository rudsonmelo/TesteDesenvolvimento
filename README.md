Um teste para medir suas habilidades, e ver se você tem as habilidades necessárias para trabalhar conosco.

## Instruções

#### Criar uma aplicação usando .Net 4.6 ou superior - angularJS ou superior

- Pode ser um console application
- Aplicação deve gerenciar CE Mercante de Conteineres.

#### Cada CE Mercante deve conter: 
    
    NumeroCE: Identificador de 19 caracteres.
	
    Um ou mais conteineres
   
#### Cada Conteiner deve conter: 
    
    Numero: Identificador de 11 caracteres.
	
	TipoOperacao: Pode ser: Cabotagem, Exportação, Importação, Transbordo, Cabotagem
	
    Capacidade Pes: Pode ser: 20 ou 40
	
	
Os registros podem ser manipulados em memória. 
(Caso seja utilizado algum ORM será considerado um diferencial)

#### As seguintes opções devem ser apresentadas:
     
     Inserir um conteiner:
        Essa opção pedira ao usuário todas as informações do conteiner.
        Se o Numero já estiver cadastrado informar o usuário e não inserir o conteiner.       
        
     Editar um conteiner existente:
        Essa opção pedira para o usuário digitar o Numero do Conteiner para pesquisa.
        Caso não encontre o conteiner, informar ao usuário.
        Caso encontre informar ao usuário as opçoes para editar que é TipoOperacao Capacidade.
     
     Deletar um conteiner existente:
        Essa opção pedira para o usuário digitar o Numero para pesquisa.
        Caso não encontre o conteiner, informar ao usuário.
        Caso encontre, perguntar a confirmação do usuário para excluir o conteiner.
     
     Listar todos os conteineres:
        Essa opção irá listar todos os conteineres cadastrado.
     
     Encontrar conteiner pelo Numero:
        Essa opção pedira para o usuário digitar o Numero para pesquisa.
        Caso não encontre o conteiner, informar ao usuário.
        Caso encontre exibir o conteiner.
     
     Sair:
        Essa opção pede a confirmação e sai da aplicação.
        
        
#### Observação: 

    Caso não saiba alguma das tecnologias abaixo. 
    Sinta-se a vontade para utilizar os conhecimentos que você tem para solucionar o problema.    
       
    
#### Desejáveis    
      Validação de campos.
      Criar quatro testes unitários.
      Usar interface.
      Usar herança.
      Usar LINQ Queries.
      Usar Lambda Expressions.
      Separar camada de negócios e camada de interação com o usuário.
      Usar e tratar exceções.
	  AngularJS ou superior.
      
#### Envio

Após finalizar, enviar o link do repositorio do github com seu projeto, além de seus dados de contato: Linkedin e Currículo.
