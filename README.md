# api-springboot-tabelafipe

**Descrição:** API Rest desenvolvida durante o curso de Spring Boot da Alura
**Objetivo:** Criar uma API para consultar os dados de veículos a partir do endereço disponibilizado em: https://deividfortuna.github.io/fipe/

# Passos realizados para a criação do projeto
1. Criação o projeto por meio do site Spring Initalizr utilizando maven e Java na versão 17
2. Criação dos pacotes: model, principal e service
3. No pacote service:
   - Criação da interface IConverteDados
   - Criação da classe ConverteDados implementando essa interface
   - Criação da classe ConsumoApi

4. No pacote principal:
   - Criação da classe Principal com a implementação da opção de exibir menu, leitura de dados, e montagem da url de busca
     
5. No arquivo TabelaFipeApplication, implementação da interface CommandLineRunner chamando a classe Principal
6. No pacote model, criação do record Dados. 
   Em seguida, criar o método obterLista na IConverteDados e implementar na classe ConverteDados
   
8. Na classe Principal, importar a classe ConverteDados e utilizar o método obterLista
9. Criação do record Modelos para representar a lista de modelos
10. Na classe Principal, concatenar o endereço da api para buscar os modelos a partir de uma marca e exibir em tela
11. Criação da record Veiculo para representar a resposta a partir dos modelos consultados

# Com a API criada
Podemos consultar os valores referentes a um modelo de carro de maneira agrupada em vez de uma consulta individual como fornecido no endereço original
