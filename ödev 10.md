### 1- City tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
>SELECT country,city FROM city<br>
LEFT JOIN country ON country.country_id = city.country_id<br>
ORDER BY country;
### 2- Customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
>SELECT first_name, last_name, payment_id FROM customer<br>
RIGHT JOIN payment ON customer.customer_id = payment.customer_id<br>
ORDER BY first_name;
### 3- Customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.
>SELECT first_name, last_name, rental_id FROM customer<br>
FULL JOIN rental ON rental.customer_id = customer.customer_id<br>
ORDER BY first_name;
