# Análise das Tabelas e Relacionamentos Mecânica

1. Cliente, Veículo e Ordem de Serviço
Cliente tem N Veículos

Ordem_Servico se relaciona com N veículos via a tabela associativa Ordem_Servico_has_Veiculos

Essa tabela também guarda a chave estrangeira do cliente, permitindo rastrear quem é o dono do veículo da OS.

Peças e Mão de Obra
Ordem_Servico tem N:M com Pecas, via Ordem_Servico_has_Pecas

Ordem_Servico também tem N:M com Mao_de_obra, via Ordem_Servico_has_Mao_de_obra

Equipes e Mecânicos
Equipe tem N Mecanicos

Ordem_Servico pode ser executada por uma ou mais equipes (relacionamento via Ordem_Servico_has_Equipe)

Equipe também pode estar associada a veículos via Equipe_has_Veiculos

![image](https://github.com/user-attachments/assets/27954afb-1839-462e-ab13-b55e89f36d3a)
