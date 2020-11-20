# :star: Importar e Exportar dados para o MariaDB

### Exportar dados para o MariaDB
```
 select id, nome, telefone into outfile "C:/RE/exporta.txt" fields terminated by ';' from lista;<br>
 ```
 ou<br>
 ```
 select * from lista into outfile "C:/RE/exporta.txt" fields terminated by ';';
 ```
 
 # Importar dados para o MariaDB
 load data local infile "C:/RE/importa.txt" into table lista fields terminated by ';';
 
# Exemplo do arquito *.txt
```
1;Isac;12345678<br>
2;Maria;12345678<br>
3;José;12345678<br>
```
