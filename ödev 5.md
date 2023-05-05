### 1-film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en uzun (length) 5 filmi sıralayınız.
SELECT * FROM film <br>
WHERE title ILIKE '%n'<br>
ORDER BY length DESC<br>
LIMIT 5;<br>
### 2-film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en kısa (length) ikinci(6,7,8,9,10) 5 filmi(6,7,8,9,10) sıralayınız.
SELECT * FROM film<br>
WHERE title ILIKE '%n'<br>
ORDER BY length <br>
OFFSET 5<br>
LIMIT 5;<br>
### 3-customer tablosunda bulunan last_name sütununa göre azalan yapılan sıralamada store_id 1 olmak koşuluyla ilk 4 veriyi sıralayınız.
SELECT * FROM customer<br>
WHERE store_id = '1'<br>
ORDER BY last_name DESC<br>
LIMIT 4;<br>
