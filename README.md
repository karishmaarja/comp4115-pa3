a)
 mysql> select area(6) as Area;
    +--------------+
    | Area(6) |
    +--------------+
    |           113.04 |
    +--------------+
    1 row in set (0.00 sec)

   mysql> select kar_area(5);
    +---------------+
    |  kar_area(5) |
    +---------------+
    |        78.5|
    +---------------+
    1 row in set (0.00 sec)

    mysql> select kar_area(22);
    +-----------------+
    | kar_area(22) |
    +-----------------+
    |        1519.76 |
    +-----------------+
    1 row in set (0.00 sec)

    mysql> select kar_area(23);
    +----------------+
    | kar_area(23) |
    +----------------+
    |            1661.06|
    +----------------+
    1 row in set (0.00 sec)
	
	
b)
    mysql> select  kar_time(324);
    +-----------------------+
    |  kar_time(324) |
    +------------- ----------+
    | 0 Hours, 5 Minutes, 24 Seconds                  |
    +------------- ----------+
    1 row in set (0.00 sec)

    mysql> select  kar_time(7721);
    +----------------------+
    |  kar_time(7721) |
    +----------- -----------+
    |  2 Hours, 8 Minutes, 41 Seconds   |
    +---------- ------------+
    1 row in set (0.00 sec)

    mysql> select kar_time(9923);
    +----------------------+
    |  kar_time(9923) |
    +----------------------+
    |  2 Hours, 45 Minutes, 23 Seconds |
    +----------------------+
    1 row in set (0.00 sec)

    mysql> select  kar_time(8682);
    +----------------------+
    |  kar_time(8682) |
    +----------------------+
    |  2 Hours, 24 Minutes, 42 Seconds   |
    +----------------------+
    1 row in set (0.00 sec)

	
#############################################################################################
	
	PART #4
	
CALL get_name('Bouloucos');
+---------------+-----------+
| first_name    | last_name |
+---------------+-----------+
| Cristinel     | Bouloucos |
| Vishv         | Bouloucos |
| Kazuhide      | Bouloucos |
| Oguz          | Bouloucos |
| Gennady       | Bouloucos |
| Tiina         | Bouloucos |
| Marla         | Bouloucos |
| Perry         | Bouloucos |








CALL avg_salary('d009'); 
+-------------+
| AVG(salary) |
+-------------+
|  58770.3665 |
+-------------+
1 row in set (0.26 sec)

Query OK, 0 rows affected (0.26 sec)





CALL count_gender('M'); 
+---------------+
| COUNT(gender) |
+---------------+
|        179973 |
+---------------+
1 row in set (0.12 sec)

 call gender('F');
        
    +---------------+
    | count(gender) |
    +---------------+
    |        120051 |
    +---------------+
    1 row in set (0.07 sec)