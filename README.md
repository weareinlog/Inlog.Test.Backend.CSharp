# CSharpTest
Um teste para medir suas habilidades com CSharp, e ver se você tem as habilidades necessárias para trabalhar conosco.

## Instruções

#### Criar uma aplicação usando .Net 4.6 ou superior.

- Pode ser uma console application
- Aplicação deve gerenciar uma frota.
- A frota contém um ou mais veículos.

#### Cada veículo deve conter: 
    
    
    Chassi[string].
	
    Tipo: Pode ser Ônibus ou Caminhão.
	
    Número de passageiros[byte]: 
            Para Caminhões será sempre 2.
            Para Ônibus será sempre 42.

    Cor[string]
   
   
Os veículos podem ser manipulados em memória. 
(Caso seja utilizado algum ORM será considerado um diferencial)

#### As seguintes opções devem ser apresentadas:
    
     
      Inserir um veículo:
        Essa opção pedira ao usuário todas as informações do veículo.
        Se o Chassi já estiver cadastrado informar o usuário e não inserir o veículo.       
        
     Editar um veículo existente:
        Essa opção pedira para o usuário digitar o chassi para pesquisa.
        Caso não encontre o veículo, informar o usuário.
        Caso encontre informar ao usuário a única opção para editar que é a cor.
     
     Deletar um veículo existente:
        Essa opção pedira para o usuário digitar o chassi para pesquisa.
        Caso não encontre o veículo, informar ao usuário.
        Caso encontre, perguntar a confirmação do usuário para excluir o veículo.
     
     Listar todos os veículos:
        Essa opção irá listar todos os veículos cadastrado.
     
     Encontrar veículo por Chassi:
        Essa opção pedira para o usuário digitar o chassi para pesquisa.
        Caso não encontre o veículo, informar ao usuário.
        Caso encontre exibir o veículo.
     
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
      Usar modificadores de acesso.
      
#### Envio

Após finalizar, enviar para o email **beinlog@inlog.com.br** o link do repositorio do github com seu projeto, além de seus dados de contato: Linkedin e Currículo.
