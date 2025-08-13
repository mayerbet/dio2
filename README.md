📦 Sistema de Gestão de Oficina Mecânica
Este projeto é um sistema simples para gerenciamento de serviços em uma oficina mecânica, incluindo cadastro de ordens de serviço, cálculo de valores e controle de pagamentos.

🛠️ Estrutura Básica
Clientes → Podem ter várias OS (relação 1:N).

Ordens de Serviço (OS) → Podem conter vários serviços (relação 1:N).

Serviços → Comparados com a tabela de referência para cálculo de valor.

Pagamentos → Associados a uma OS (relação 1:N).

📊 Tabela de Referência
Para padronizar valores, é utilizada uma Tabela de Referência de Mão de Obra, onde cada tipo de serviço tem:

Descrição

Código

Valor base
