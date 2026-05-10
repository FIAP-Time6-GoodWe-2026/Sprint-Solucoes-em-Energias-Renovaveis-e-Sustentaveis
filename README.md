# Sprint-Solucoes-em-Energias-Renovaveis-e-Sustentaveis
Repositório para realização das sprints de Computer Organization and Architecture - (Prof: Álvador Gonçalves)

1 – ChargeGrid Intelligence
Desafio FIAP + GoodWe Challenge 2026 | Sprint 1 – Soluções em Energias Renováveis e Sustentáveis

2 – Integrantes

Alan Junio Araujo de Souza - RM 574112
Arthur Vettorazzo de Souza - RM 569445
Brayan Barbosa Dos Santos - RM 573682
Giovanne Gomes Petenuci - RM 574091
Gustavo Zibini Belizario - RM 561376
Luiz Otávio Brito Freixo - RM 561376

3 – Problema Apresentado

O problema central reside na ausência de mecanismos tecnológicos integrados nos eletropostos comerciais capazes de orquestrar a potência, registrar ciclos de operação, realizar o faturamento inteligente e estabelecer uma comunicação eficiente com a rede elétrica. Sem uma camada de inteligência de software, as estações operam de forma isolada e geram sobrecargas severas na rede da concessionária durante os horários de pico. Essa fragmentação técnica resulta em um modelo de operação insustentável, pois a incapacidade de gerir a demanda em tempo real impede a eficiência energética e eleva os custos operacionais por falta de previsibilidade e controle.

4 – Justificativa Proposta

A solução ChargeGrid Intelligence justifica-se pela necessidade de otimizar o consumo de energia proveniente da rede elétrica, transformando dados brutos em decisões inteligentes de gestão de demanda. Ao utilizar a plataforma para integrar os dados de telemetria da infraestrutura GoodWe, o projeto permite o controle da carga de forma totalmente via software. Essa abordagem evita a sobrecarga da infraestrutura local da concessionária e ajuda a "achatar" a curva de consumo nacional. Dessa forma, reduz-se a necessidade de acionamento de usinas termelétricas poluentes nos horários de maior procura, promovendo uma operação mais limpa e alinhada às metas de sustentabilidade global.

5 – Proposta de Solução

O projeto propõe uma plataforma de software inteligente focada na orquestração energética através de três pilares:

5.1 - Monitoramento e Orquestração Centralizada: Uma aplicação de gestão que centraliza as informações de consumo da rede. A inteligência do software processa esses dados para ajustar dinamicamente a potência disponível em cada carregador, garantindo eficiência sem a necessidade de intervenções físicas ou hardware adicional.

5.2 - Otimização de Demanda via Software: Através da integração direta com as APIs da GoodWe, a aplicação monitora o consumo total do eletroposto. O sistema executa algoritmos que priorizam o carregamento eficiente e seguro, respeitando os limites contratuais de potência e preparando o ecossistema para futuras integrações com energias renováveis.

5.3 - Interface de Tarifação e Comunicação: A aplicação gerencia a tarifação dinâmica, utilizando o faturamento como uma ferramenta de incentivo. O software comunica aos usuários os melhores momentos para recarga, promovendo um equilíbrio consciente entre a demanda do veículo e a capacidade da rede elétrica.

6 – Arquitetura Utilizada

A arquitetura da solução é baseada em uma camada de software de alta integração:

Integração de Dados (API Economy): Consumo de dados em tempo real dos sistemas de monitoramento da GoodWe para análise do fluxo energético vindo da concessionária.

Protocolos de Comunicação em Nuvem: Utilização do protocolo OCPP para o comando remoto dos carregadores e MODBUS (via gateways de rede existentes) para a leitura dos medidores, permitindo que a aplicação controle todo o ecossistema de forma centralizada.

Camada de Lógica e Inteligência: Algoritmos de processamento de dados que automatizam a tomada de decisão sobre a distribuição de potência, garantindo que a orquestração seja feita de forma ágil e precisa.

7 – Impactos Esperados (Viabilidade Técnica e de Negócio)

Viabilidade Técnica: Por ser uma solução focada em aplicação e integração de APIs e protocolos de mercado, a implementação é escalável e de rápida execução, utilizando a infraestrutura tecnológica já disponível nos eletropostos modernos.

Impacto Ambiental: A orquestração inteligente via software evita picos de demanda que sobrecarregam o sistema interligado nacional, promovendo um uso racional da energia e diminuindo a pegada de carbono indireta da operação.

Viabilidade de Negócio: Redução imediata de custos com multas de ultrapassagem de demanda e otimização da receita através da gestão dinâmica de preços. O modelo focado em software reduz custos de manutenção de hardware próprio e posiciona o projeto como uma solução de ponta em governança ambiental e eficiência operacional (ESG).


8- Link pitch:

https://_____________________
