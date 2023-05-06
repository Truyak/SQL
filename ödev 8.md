### 1- Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
> CREATE TABLE employee(<br>
	id INT,<br>
	name VARCHAR(50),<br>
	birthday DATE,<br>
	email VARCHAR(100)<br>
);
### 2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
>insert into employee (id, name, birthday, email) values (1, 'Dewie', '2010-05-06', 'dradden0@spotify.com');<br>
insert into employee (id, name, birthday, email) values (2, 'Angy', '2021-01-22', 'agarrish1@webs.com');<br>
insert into employee (id, name, birthday, email) values (3, 'Dale', '1965-03-13', 'dsutterfield2@hugedomains.com');<br>
insert into employee (id, name, birthday, email) values (4, 'Rosabelle', '1971-10-23', 'rbianco3@ning.com');<br>
insert into employee (id, name, birthday, email) values (5, 'Kandace', '2018-07-29', 'kdavidge4@amazon.com');<br>
insert into employee (id, name, birthday, email) values (6, 'Kennan', '2021-01-07', 'kolynn5@feedburner.com');<br>
insert into employee (id, name, birthday, email) values (7, 'Laverna', '1990-04-18', 'lhayer6@hc360.com');<br>
insert into employee (id, name, birthday, email) values (8, 'Tamarah', '2015-06-12', 'tazema7@linkedin.com');<br>
insert into employee (id, name, birthday, email) values (9, 'Alvan', '1971-05-08', 'adundredge8@sourceforge.net');<br>
insert into employee (id, name, birthday, email) values (10, 'Amelina', '1998-11-27', 'amuge9@amazonaws.com');<br>
insert into employee (id, name, birthday, email) values (11, 'Laurice', '2021-10-08', 'lawmacka@bizjournals.com');<br>
insert into employee (id, name, birthday, email) values (12, 'Nils', '1962-12-19', 'nmccullyb@imageshack.us');<br>
insert into employee (id, name, birthday, email) values (13, 'Noni', '1967-01-09', 'nsilvesterc@t.co');<br>
insert into employee (id, name, birthday, email) values (14, 'Vivi', '1975-10-21', 'vgiblingd@twitpic.com');<br>
insert into employee (id, name, birthday, email) values (15, 'Anni', '1998-09-28', 'acapponere@ca.gov');<br>
insert into employee (id, name, birthday, email) values (16, 'Antonio', '1960-10-04', 'abeamentf@cdc.gov');<br>
insert into employee (id, name, birthday, email) values (17, 'Birdie', '2001-09-24', 'bmelving@livejournal.com');<br>
insert into employee (id, name, birthday, email) values (18, 'Mordecai', '1999-09-08', 'mcrummeyh@cbsnews.com');<br>
insert into employee (id, name, birthday, email) values (19, 'Frank', '2004-11-08', 'fpleacei@blogger.com');<br>
insert into employee (id, name, birthday, email) values (20, 'Vivienne', '1985-10-18', 'vmcpaikj@digg.com');<br>
insert into employee (id, name, birthday, email) values (21, 'Giacomo', '1975-10-18', 'gboundeyk@ted.com');<br>
insert into employee (id, name, birthday, email) values (22, 'Joe', '1999-09-02', 'jchallenderl@washington.edu');<br>
insert into employee (id, name, birthday, email) values (23, 'Othelia', '1976-03-11', 'omattiazzom@shutterfly.com');<br>
insert into employee (id, name, birthday, email) values (24, 'Emmery', '1963-03-04', 'ebraznelln@etsy.com');<br>
insert into employee (id, name, birthday, email) values (25, 'Giralda', '1996-10-10', 'gblytho@bravesites.com');<br>
insert into employee (id, name, birthday, email) values (26, 'Stafford', '2007-11-06', 'scrump@upenn.edu');<br>
insert into employee (id, name, birthday, email) values (27, 'Goldina', '2015-08-22', 'grouthornq@dion.ne.jp');<br>
insert into employee (id, name, birthday, email) values (28, 'Nealy', '1968-10-08', 'nwoodisonr@prlog.org');<br>
insert into employee (id, name, birthday, email) values (29, 'Crawford', '1975-03-11', 'cparmbys@arstechnica.com');<br>
insert into employee (id, name, birthday, email) values (30, 'Amos', '1980-06-09', 'ajopsont@deliciousdays.com');<br>
insert into employee (id, name, birthday, email) values (31, 'Leonard', '1995-09-01', 'lbellou@zdnet.com');<br>
insert into employee (id, name, birthday, email) values (32, 'Karleen', '1992-01-25', 'ktristramv@tripod.com');<br>
insert into employee (id, name, birthday, email) values (33, 'Vasilis', '2006-11-12', 'vtheuffw@reverbnation.com');<br>
insert into employee (id, name, birthday, email) values (34, 'Aldus', '1971-10-22', 'ababerx@blinklist.com');<br>
insert into employee (id, name, birthday, email) values (35, 'Cherry', '1964-03-17', 'cmcgorleyy@theatlantic.com');<br>
insert into employee (id, name, birthday, email) values (36, 'Gisele', '1977-06-30', 'gvahlz@com.com');<br>
insert into employee (id, name, birthday, email) values (37, 'Risa', '1989-11-19', 'rdelort10@amazon.co.jp');<br>
insert into employee (id, name, birthday, email) values (38, 'Rivkah', '2017-12-22', 'rholdren11@quantcast.com');<br>
insert into employee (id, name, birthday, email) values (39, 'Arlie', '1995-02-06', 'afold12@dailymotion.com');<br>
insert into employee (id, name, birthday, email) values (40, 'Barth', '1991-10-07', 'bcopcutt13@geocities.com');<br>
insert into employee (id, name, birthday, email) values (41, 'Eveleen', '2001-10-10', 'ericarde14@tinypic.com');<br>
insert into employee (id, name, birthday, email) values (42, 'Emmeline', '2015-07-19', 'egeratt15@shutterfly.com');<br>
insert into employee (id, name, birthday, email) values (43, 'Thatch', '2008-03-18', 'tdainton16@umn.edu');<br>
insert into employee (id, name, birthday, email) values (44, 'Joey', '2017-04-11', 'jkynman17@google.fr');<br>
insert into employee (id, name, birthday, email) values (45, 'Christel', '1995-08-07', 'citskovitz18@t.co');<br>
insert into employee (id, name, birthday, email) values (46, 'Edee', '1968-01-01', 'ejordan19@scientificamerican.com');<br>
insert into employee (id, name, birthday, email) values (47, 'Vail', '1998-12-23', 'vedward1a@biglobe.ne.jp');<br>
insert into employee (id, name, birthday, email) values (48, 'Porty', '1973-07-12', 'pcalvey1b@businessweek.com');<br>
insert into employee (id, name, birthday, email) values (49, 'Conant', '1990-06-29', 'cburnep1c@samsung.com');<br>
insert into employee (id, name, birthday, email) values (50, 'Cassie', '2003-12-07', 'cmerrgen1d@dot.gov');
### 3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
>UPDATE employee<br>
SET name = 'Kerem',<br>
	  birthday = '2004-12-03'<br>
Where email = 'ktristramv@tripod.com';<br>

>UPDATE employee<br>
SET name = 'Patikacı',<br>
	birthday = '1983-03-12'<br>
Where id = '16';

>UPDATE employee<br>
SET email = 'straight@falling.com',<br>
	birthday = '1990-10-06'<br>
Where name ='Dale';

>UPDATE employee<br>
SET name = 'Hamdi',<br>
	email = 'cream@butter.com'<br>
Where birthday = '1975-10-18';

>UPDATE employee<br>
SET name = 'Freddie',<br>
	birthday = '2010-04-17'<br>
Where email = 'fpleacei@blogger.com';

### 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
>DELETE FROM employee<br>
WHERE id = '13';

>DELETE FROM employee<br>
WHERE name = 'Mordecai';

>DELETE FROM employee<br>
WHERE email LIKE 'dra%@spotify.com';

>DELETE FROM employee<br>
WHERE birthday = '1975-10-21';

>DELETE FROM employee<br>
WHERE name ILIKE 'f%e'<br>
RETURNING *;
