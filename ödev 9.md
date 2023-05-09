### 1- City tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
> SELECT country, city  FROM country<br>
INNER JOIN city ON city.country_id = country.country_id;
### 2- Customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
> SELECT first_name, last_name, payment_id FROM payment<br>
INNER JOIN customer ON customer.customer_id = payment.customer_id;
### 3- Customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
> SELECT first_name, last_name, rental_id FROM rental<br>
INNER JOIN customer ON customer.customer_id = rental.customer_id;
