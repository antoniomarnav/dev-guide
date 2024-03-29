# APIs publicas
- [Repo genérico](https://github.com/public-apis/public-apis)
- [Gobierno de España](https://opendata.esri.es/)
- [Estado Español](https://datos.gob.es/es)

# Servidores de correo
- [Amazon SES](https://aws.amazon.com/es/ses/)
- [Resend](https://resend.com/)

# Buenas practicas SQL
- [𝗧𝗼𝗽 𝟮𝟬 𝗦𝗤𝗟 𝗾𝘂𝗲𝗿𝘆 𝗼𝗽𝘁𝗶𝗺𝗶𝘇𝗮𝘁𝗶𝗼𝗻 𝘁𝗲𝗰𝗵𝗻𝗶𝗾𝘂𝗲𝘀 by Dr Milan Milanović](https://twitter.com/milan_milanovic/status/1758831924380880968?s=12&t=D4rOQTwN9j2NygNchswAxA)
1. Create an index on huge tables (>1.000.000) rows
2. Use EXIST() instead of COUNT() to find an element in the table
3. SELECT fields instead of using SELECT *
4. Avoid Subqueries in WHERE Clause
5. Avoid SELECT DISTINCT where possible
6. Use WHERE Clause instead of HAVING
7. Create joins with INNER JOIN (not WHERE)
8. Use LIMIT to sample query results
9. Use UNION ALL instead of UNION wherever possible
10. Use UNION where instead of WHERE ... or ... query.
11. Run your query during off-peak hours
12. Avoid using OR in join queries
14. Choose GROUP BY over window functions
15. Use derived and temporary tables
16. Drop the index before loading bulk data
16. Use materialized views instead of views
17. Avoid != or <> (not equal) operator
18. Minimize the number of subqueries
19. Use INNER join as little as possible when you can get the same output using LEFT/RIGHT join.
20. Frequently try to use temporary sources to retrieve the same dataset.
