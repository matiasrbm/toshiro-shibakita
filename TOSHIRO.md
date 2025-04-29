# A História de TOSHIRO SHIBAKITA: Aplicações em Bare Metal até a Conteinerização em Nuvem Pública

## INTRODUÇÃO

A história de Toshiro Shibakita é fictícia e foi utilizada durante o curso "Linux para Iniciantes" para exemplificar como o uso de nuvem pública e microsserviços pode transformar o seu negócio e aumentar muito o desempenho dos serviços usados em servidores.

Toshiro era dono do SHIBAKITA HIPERMERCADO I, que utilizava nuvem local para manter seus serviços: um servidor com banco de dados para leitura dos códigos de barra, para cálculo da compra no caixa, para gestão de estoque, etc.

Mas Toshiro percebeu que seu servidor tinha alto custo e seus negócios não iam bem, sem contar o preço para manter essas máquinas: discos, switch, modem, cabeamento, ar condicionado...

Além disso, Toshiro estava preocupado com as vendas nas vésperas de Natal e Ano Novo, pois poderiam haver apagões de energia com os fogos e estresse do servidor com a sobrecarga de clientes.

Isso impedia o crescimento de sua rede de mercados.

Por esses motivos e outros, Shibakita foi em busca de uma solução.

## NUVEM PÚBLICA

Entrando em contato com uma analista de TI, Julpira das Neves, ele percebe as desvantagens em manter a nuvem privada:

* Problemas de segurança da informação (lógica e física);
* Custo da mão de obra especializada (Data Center tem uma ciência complexa);
* Custo de hardware;
* Custo da energia elétrica;
* Instabilidade da energia elétrica;
* Custo para manter geradores;
* Outras despesas inesperadas com componentes.

E as vantagens para migrar para nuvem pública:

* Pagar somente o serviço utilizado;
* Fácil contratação: Oracle, Cloud, AWS, Azure...
* Escalabilidade: criação rápida de servidores e serviços que distribuem a carga de informações de modo autônomo;
* Performance.

Vendo esse cenário, a esposa de Toshiro sugeriu que eles migrassem para uma arquitetura de microsserviços, já que usariam nuvens públicas.

## MICROSSERVIÇOS

Microsserviços é uma arquitetura de software que constrói aplicações distribuindo elas por servidores independentes, onde cada serviço é executado separadamente, conectados por API.

Geralmente utilizam JSON nessa comunicação entre servidores, e podem ser escritos em várias linguagens de programação.
