# Migração das bases de dados SQL Server da VM1 para VM2. 

Aqui compartilho alguns passos da migração que realizei das bases de dados do meu laboratório para outro servidor virtual.

- DNS e DC já foram transferidos anteriormente, agora estou no processo de transferência das bases de dados que existe na instância.

1. Mapeamento do servidor via pasta de rede para a transferência dos arquivos
2. Criação do script responsável por realizar o backup de todas as bases que não sejam do sistema.
3. Criação do script responsável por fazer bakcup das bases do sistema.
4. Transferência dos dados.
