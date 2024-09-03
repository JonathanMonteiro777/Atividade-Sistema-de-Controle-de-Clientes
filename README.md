# Sistema de Controle de Clientes

Este projeto demonstra a implementação de um sistema de controle de clientes em C#, utilizando os conceitos da Programação Orientada a Objetos (POO).

## Objetivo:

### Desenvolver um sistema que:

+ Cadastre clientes (pessoas físicas e jurídicas).

+ Calcule o imposto a pagar, considerando o tipo de cliente.

+ Apresente os dados do cliente e os resultados dos cálculos em tela.

### Requisitos:

+ Entrada de dados via console.

+ Implementação dos conceitos de POO: abstração, herança, polimorfismo e encapsulamento.

### Diagrama de Classes:

### Clientes
+ nome : string
+ endereco : string
+ valor : float
+ valor_imposto : float
+ total : float
+ Pagar_Imposto(v : float) : void
### Pessoa_Fisica
+ cpf : string
+ rg : string
### Pessoa_Juridica
+ cnpj : string
+ ie : string
+ Pagar_Imposto(v : float) : void

## Funcionalidades:

### Cadastro:

Permite cadastrar clientes, especificando se são pessoas físicas ou jurídicas.

Coleta informações específicas para cada tipo de cliente (CPF/RG ou CNPJ/IE).

### Cálculo de Imposto:

Calcula o imposto a pagar com base no valor da compra e no tipo de cliente (10% para pessoa física e 20% para pessoa jurídica).

### Apresentação dos Dados:

Exibe em tela os dados do cliente e o valor do imposto calculado.

### Instruções de Execução:

Instalar o .NET SDK: Se ainda não tiver instalado, faça o download e instale o .NET SDK em seu sistema.

Clonar o Repositório: Clone este repositório para sua máquina local.

Compilar o Projeto: Abra o terminal no diretório do projeto e execute o comando dotnet build.

Executar o Projeto: Execute o comando dotnet run para iniciar o programa.

### Como usar o sistema:

O sistema irá solicitar informações básicas do cliente (nome, endereço) e o tipo (Pessoa Física (f) ou Jurídica (j)).

Insira as informações solicitadas e pressione Enter.

O sistema irá pedir informações específicas de acordo com o tipo de cliente.

Insira os dados e o valor da compra, e pressione Enter.

O sistema mostrará os dados do cliente e o valor total a pagar, incluindo o imposto.

### Observações:
Este projeto foi desenvolvido como atividade prática do curso FullStack do SENAI, visando aprofundar o conhecimento em Codificação Back-End.
