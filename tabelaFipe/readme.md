Objetivo: Criar uma API com Spring Boot para acessar os dados referentes aos modelos de carro 
Endereço: https://deividfortuna.github.io/fipe/

Passos:
1. Criar o projeto por meio do site Spring Initalizr

2. Criar os pacotes: model, principal e service

3. No pacote service:
   - Criar a interface IConverteDados
   - Criar a classe ConverteDados implementando essa interface
   - Criar a classe ConsumoApi

4. No pacote principal:
   - Criar a classe Principal com a implementação da opção de exibir menu, leitura de dados, e montagem da url de busca

5. No arquivo TabelaFipeApplication, implementar a interface CommandLineRunner chamando a classe Principal

6. No pacote model criar o record Dados. 
   Em seguida, criar o método obterLista na IConverteDados e implementar na classe ConverteDados

7. Na classe Principal, importar a ConverteDados e utilizar o método obterLista

8. Criar o record Modelos para representar a lista de modelos

9. Na classe Principal, concatenar o endereço da api para buscar os modelos a partir de uma marca e exibir em tela

10. Criar o record Veiculo para representar a resposta a partir dos modelos consultados