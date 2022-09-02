# Mapeamento de funcionalidades
### Tiwnio Net

|Número|REQUISITOS FUNCIONAIS            | REQUISITOS NÃO FUNCIONAIS   |
|----------    |--------------------------------|-----------------------------|
|1           | O sistema permitirá cadastrar os funcionários       | Segurança → Fator 2FA para funcionários                    |
|2            | Para operar o sistema, o funcionário deverá realizar o login, a fim de se manter um registro de uso          | Disponibilidade → Disponibilidade de acesso remoto por qualquer dispositivo registrado no sistema|
|3             | Os produtos utilizados serão catalogadas no sistema         | Desempenho → Renderização dos dados em ate 2 segundos|
|4             | A frota sera cadastrada no sistema, a fim de se manter um dado preciso do mesmo        | Banco de dados → Construído em MongoDB   |
|5            | O sistema irá realizar um contro dos produtos utilizados incluindo data, veiculo e funcionário           | Interface → Interface contruida perante os requisistos do cliente        |
|6          | Irá apresentar um histórico de pesquisa e de alteração                    | Tolerancia à falhas → Continuar funcionando após uma base de dados cair              |
|7          | O sistema irá alertar quando deverá ser realizada as futuras manutenções do veículo              | Projetado → Sistema Compilado em Java           |
|8             | Será possível verificar o status de um veículo individual, perante a sua última atualização         | Manutenibilidade → Documentação do código do projeto a fim de facilitar a manutenção do sistema            |
|9        | Terá um alerta para avisar a necessidade da aquisição de material       | Dashboard → Dashboard para facilitar de visualização dos dados presentes            |
|10           |Haverá um registro dos dados de quilometragem dos veiculos| Usabilidade → Simplificação dos processos do sistema a fim de facilitar o entendimento pelo usuário                  |
<!--https://excelcoaching.com.br/wp-content/uploads/2021/06/Planilha-Controle-de-Entragas-4-1536x958.png-->
