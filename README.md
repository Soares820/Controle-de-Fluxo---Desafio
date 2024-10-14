texto
# Desafio Controle de Fluxo

Este projeto é uma implementação em Java que demonstra o uso de controle de fluxo e tratamento de exceções. O sistema recebe dois números inteiros como parâmetros e imprime uma sequência de números incrementados, validando se o primeiro número é menor que o segundo.

## Funcionalidades

- Recebe dois números inteiros via terminal.
- Imprime os números entre os dois parâmetros, incluindo ambos.
- Lança uma exceção customizada se o primeiro parâmetro for maior que o segundo.

## Tecnologias Utilizadas

- Java 8 ou superior
- IDE (como IntelliJ IDEA, Eclipse ou NetBeans)

## Estrutura do Projeto

O projeto contém as seguintes classes:

1. **Contador.java**: Classe principal que contém a lógica do programa.
2. **ParametrosInvalidosException.java**: Classe que representa a exceção customizada utilizada para validar os parâmetros de entrada.

## Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter o Java instalado em sua máquina. Você pode verificar a instalação do Java com o seguinte comando:

```bash
java -version

Compilação e Execução
Clonar este repositório:
bater
git clone https://github.com/seuusuario/DesafioControleFluxo.git

Navegue até o diretório do projeto:
bater
cd DesafioControleFluxo

Compilar como classes:
bater
javac Contador.java ParametrosInvalidosException.java

Execute um principal de classe:
bater
java Contador

Siga as instruções no terminal para inserir os parâmetros.
Exemplo de uso
Ao executar o programa, você verá as seguintes instruções no terminal:
texto
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30

E a saída será:
texto
Imprimindo o número 12
Imprimindo o número 13
Imprimindo o número 14
...
Imprimindo o número 30

Se você inserir um primeiro parâmetro maior que o segundo, como:
texto
Digite o primeiro parâmetro:
30
Digite o segundo parâmetro:
12

A saída será:
texto
O segundo parâmetro deve ser maior que o primeiro

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou solicitações pull.
Licença
Este projeto está licenciado sob uma licença do MIT .
texto

### Instruções Finais

1. **Crie um diretório** chamado `DesafioControleFluxo` em sua máquina local.
2. **Crie os arquivos** `Contador.java` e `ParametrosInvalidosException.java` dentro desse diretório e cole os códigos correspondentes.
3. **Crie um arquivo** chamado `README.md` e cole o conteúdo do README fornecido.
4. **Suba os arquivos** para um repositório no GitHub seguindo as instruções contidas no README.

