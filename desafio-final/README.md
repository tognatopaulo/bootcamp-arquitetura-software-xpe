# Desenvolvimento da Solução do Desafio Final

Arquitetura em nuvem escalável, com alta disponibilidade e resiliência para uma aplicação de vendas online, utilizando as boas práticas de arquitetura em nuvem e observando os pontos solicitados no desafio, vide abaixo:
•	Uso de múltiplas zonas de disponibilidade para garantir continuidade do serviço mesmo em caso de falha de uma zona.
•	Balanceamento de carga para distribuir o tráfego entre as máquinas virtuais (VMs).
•	Escalonamento automático das VMs de acordo com a demanda, com um mínimo de 3 e máximo de 6 instâncias, usando imagens Linux.
•	Provisão de um serviço de banco de dados gerenciado (PaaS) que garanta alta disponibilidade e segurança para os dados da aplicação.
•	Configuração de controle de acesso (IAM) para que as VMs tenham permissões de leitura e escrita no banco de dados provisionado.
