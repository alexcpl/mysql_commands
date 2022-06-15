SELECT job FROM mytable WHERE id BETWEEN 10 AND 15

or

SELECT job FROM mytable WHERE id > 10 AND id < 15

##Select truncate output
select id, SUBSTRING(full_name,1, 32), age FROM user


