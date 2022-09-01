# Mapeamento de funcionalidades
### Tiwnio Net

|Número|REQUSITOS FUNCIONAIS            | REQUISITOS NÃO FUNCIONAIS   |
|----------    |--------------------------------|-----------------------------|
|1           | O sistema permitira cadastras os funcionários       | Segurança → Fator 2FA para funcionários                    |
|2            | Para operar o sistema o funcionário devera realizar o login, afim de se manter um registro de uso          | Disponibilidade → Disponibilidade de acesso remoto por qualquer dispositivo registrado no sistema|
|3             | Os produtos utilizados serão registados no sistema         | Desempenho → Renderização dos dados em ate 2segundos|
|4             | A frota sera cadastrada no sistema, afim de se manter um dado preciso do mesmo        | Banco de dados → Construido em MongoDB   |
|5            | O sistema ira realizar um contro dos produtos utilizados incluindo data, veiculo e funcionário           | Interface → Interface contruida perante os requisistos do cliente        |
|6          | Ira apresentar um historico de pesquisa e de alteração                    |Tolerancia a falhas → Continuar funcionando após uma base de dados cair              |
|7          | O sistema ira alertar quando devera ser realizada as futuras manuteções do veiculo              | Projetado → Sistema Compilado em JAVA           |
|8             | Sera possivel verificar o status de um veiculo individual, perante a suaultima atualização         | Manutenibilidade → Documentação do código do projeto afim de facilitar a manutenção do sistema            |
|9        | Se mantera um minimo aceitavel antes do sistema acusar nescessidade da aquisição de material       | Dashboard → Dashboard para a facilidade de visualização dos dados presentes            |
|10           |Havera um registro dos dados de quilometragem individual dos veiculos| Usabilidade → Simplificação dos processos do sistema afim de facilitar o entendimento pelo usuario                  |
