# Importar e Exportar dados para o MariaDB
:star:
# Exportar dados para o MariaDB
 select id, nome, telefone into outfile "C:/RE/exporta.txt" fields terminated by ';' from lista;
 ou
 select * from lista into outfile "C:/RE/exporta.txt" fields terminated by ';';
 
 # Importar dados para o MariaDB
 load data local infile "C:/RE/importa.txt" into table lista fields terminated by ';';
