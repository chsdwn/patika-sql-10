```sql
1. SELECT city.city, country.country FROM city LEFT JOIN country ON city.country_id = country.country_id;
```
```sql
2. SELECT payment.payment_id, customer.first_name, customer.last_name FROM customer
      RIGHT JOIN payment ON payment.customer_id = customer.customer_id;
```
```sql
3. SELECT rental.rental_id, customer.first_name, customer.last_name FROM rental
      FULL JOIN customer ON rental.customer_id = customer.customer_id;
```
