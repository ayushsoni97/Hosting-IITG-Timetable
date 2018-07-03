-- packages used

Cassandra 3.11.0 | CQL spec 3.4.4 | Native protocol v4]
cqlsh
Python v2.7
Flask and Html for web interface


Logic -- 
 first got the total no of entries where hashtag = BoxingDay and inserted them into a table (loc_counter)with
 count attribute which can be only used with cassandra-UPDATE command, and incresed count one by one on each row.
 But also need to order entries according to frequency, so inserted all the data in another table(loc_count) with
 count as cluster key (ordered descending).Ordering can't be done in first table (loc_counter ) as count cant be 
 updated then.Similar logic used in q10.

 files SUbmitted -- 
 schemaQues1/10.txt -- given schemas of tables used in procedure
 OutQues1/10.csv -- output of both tables queries.
 programQues1/10.txt -- core programs used in evaluation



