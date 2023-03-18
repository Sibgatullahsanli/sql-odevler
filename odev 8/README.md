[PATİKA](https://app.patika.dev/) dev in Php dersleri çerçevesinde çelıştığımız SQL için verilen 8.ci ödevimiz.

[Patika Profilim](https://app.patika.dev/sibgat)

[GitHub Profilim](https://github.com/Sibgatullahsanli)

Merhabalar,

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

Kolay Gelsin.

CEVAPLAR:



1. 

CREATE TABLE employee(
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
)

2. 

insert into employee (id, name, birthday, email) values (1, 'Natividad Garretts', '1996-12-30', 'ngarretts0@posterous.com');
insert into employee (id, name, birthday, email) values (2, 'Umeko Heakey', '1958-06-06', null);
insert into employee (id, name, birthday, email) values (3, 'Wilfrid Buffey', null, 'wbuffey2@wp.com');
insert into employee (id, name, birthday, email) values (4, 'Kent Brende', '1989-05-29', 'kbrende3@nyu.edu');
insert into employee (id, name, birthday, email) values (5, 'Dame Ulrik', '1997-12-17', 'dulrik4@wisc.edu');
insert into employee (id, name, birthday, email) values (6, 'Tabbi Bowell', '1968-12-18', 'tbowell5@dropbox.com');
insert into employee (id, name, birthday, email) values (7, 'Kennedy Caisley', null, 'kcaisley6@nih.gov');
insert into employee (id, name, birthday, email) values (8, 'Halie Merigeau', '1990-10-22', 'hmerigeau7@amazon.co.uk');
insert into employee (id, name, birthday, email) values (9, 'Rickert Shales', '1981-04-12', 'rshales8@a8.net');
insert into employee (id, name, birthday, email) values (10, 'Ibrahim Thireau', '1952-12-13', null);
insert into employee (id, name, birthday, email) values (11, 'Fernanda Tomley', '1953-03-02', 'ftomleya@washingtonpost.com');
insert into employee (id, name, birthday, email) values (12, 'Dar Geraldi', null, 'dgeraldib@theguardian.com');
insert into employee (id, name, birthday, email) values (13, 'Hephzibah Cuesta', '1967-09-12', 'hcuestac@youku.com');
insert into employee (id, name, birthday, email) values (14, 'Allissa Gallo', '1991-12-21', null);
insert into employee (id, name, birthday, email) values (15, 'Shaina Pithcock', '1999-06-02', 'spithcocke@hc360.com');
insert into employee (id, name, birthday, email) values (16, 'Darrel Finney', '1965-10-15', 'dfinneyf@skype.com');
insert into employee (id, name, birthday, email) values (17, 'Paule Remer', '1954-12-10', 'premerg@businessweek.com');
insert into employee (id, name, birthday, email) values (18, 'Euell De Stoop', '1980-10-20', 'edeh@diigo.com');
insert into employee (id, name, birthday, email) values (19, 'Penny Burdus', '1963-10-14', 'pburdusi@blinklist.com');
insert into employee (id, name, birthday, email) values (20, 'Norine Loney', '1963-07-09', 'nloneyj@so-net.ne.jp');
insert into employee (id, name, birthday, email) values (21, 'Tome Van Hault', '1988-04-28', 'tvank@mapquest.com');
insert into employee (id, name, birthday, email) values (22, 'Renata Cauderlie', '1989-03-07', 'rcauderliel@techcrunch.com');
insert into employee (id, name, birthday, email) values (23, 'Norah Sheasby', '1983-01-11', 'nsheasbym@wiley.com');
insert into employee (id, name, birthday, email) values (24, 'Blanch Baalham', '1970-06-13', 'bbaalhamn@biblegateway.com');
insert into employee (id, name, birthday, email) values (25, 'Roxine Happel', '1983-01-31', 'rhappelo@craigslist.org');
insert into employee (id, name, birthday, email) values (26, 'Jard Ritchings', '1984-11-07', 'jritchingsp@statcounter.com');
insert into employee (id, name, birthday, email) values (27, 'Claudia Haggart', '1983-02-01', 'chaggartq@jimdo.com');
insert into employee (id, name, birthday, email) values (28, 'Ardisj St. Leger', '1954-04-12', 'astr@yellowpages.com');
insert into employee (id, name, birthday, email) values (29, 'Sioux Mallock', '1991-07-26', null);
insert into employee (id, name, birthday, email) values (30, 'Erhart Bick', '1970-06-18', 'ebickt@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (31, 'Giulia Wrightham', '1997-09-15', 'gwrighthamu@multiply.com');
insert into employee (id, name, birthday, email) values (32, 'Ravid Hemshall', '1988-10-23', 'rhemshallv@google.ru');
insert into employee (id, name, birthday, email) values (33, 'Rudd Leinweber', '1964-04-28', 'rleinweberw@google.cn');
insert into employee (id, name, birthday, email) values (34, 'Randolph Handrock', '1978-07-28', 'rhandrockx@engadget.com');
insert into employee (id, name, birthday, email) values (35, 'Demetris Berkley', null, 'dberkleyy@friendfeed.com');
insert into employee (id, name, birthday, email) values (36, 'Marianna Shedden', '1958-08-30', 'msheddenz@google.pl');
insert into employee (id, name, birthday, email) values (37, 'Cyndi Jorck', '1982-12-23', 'cjorck10@usnews.com');
insert into employee (id, name, birthday, email) values (38, 'Hayden Lowndesbrough', '1962-03-06', 'hlowndesbrough11@ezinearticles.com');
insert into employee (id, name, birthday, email) values (39, 'Tish Strelitzer', '1964-05-10', 'tstrelitzer12@elpais.com');
insert into employee (id, name, birthday, email) values (40, 'Breena Zohrer', null, 'bzohrer13@tmall.com');
insert into employee (id, name, birthday, email) values (41, 'Jacinthe Laister', '1980-05-03', 'jlaister14@yellowbook.com');
insert into employee (id, name, birthday, email) values (42, 'Rollo Conningham', '1997-03-23', 'rconningham15@mediafire.com');
insert into employee (id, name, birthday, email) values (43, 'Robin Dimsdale', null, null);
insert into employee (id, name, birthday, email) values (44, 'Giustino Gilbee', '1980-08-14', 'ggilbee17@blinklist.com');
insert into employee (id, name, birthday, email) values (45, 'Franny Zealander', '1969-05-29', 'fzealander18@ucsd.edu');
insert into employee (id, name, birthday, email) values (46, 'Kahlil Zelley', '1994-08-13', 'kzelley19@yolasite.com');
insert into employee (id, name, birthday, email) values (47, 'Mace Azema', '1958-08-30', 'mazema1a@tuttocitta.it');
insert into employee (id, name, birthday, email) values (48, 'Correna Mogra', '1971-07-04', 'cmogra1b@nationalgeographic.com');
insert into employee (id, name, birthday, email) values (49, 'Allyce Rickerd', '1973-04-14', 'arickerd1c@slideshare.net');
insert into employee (id, name, birthday, email) values (50, 'Merrilee Rains', '1971-05-28', 'mrains1d@house.gov');

3. 

UPDATE employee
SET name = 'Beyza'
WHERE id < 10;

UPDATE employee
SET birthday = '1996-04-25'
WHERE name LIKE 'A%';

UPDATE employee
SET email = 'google@google.org'
WHERE email LIKE '%com%';

UPDATE employee
SET name = 'Geckin'
WHERE birthday BETWEEN '1950-01-01' AND '1970-01-01';

UPDATE employee
SET name = 'Erkan'
WHERE name = 'Beyza' and id BETWEEN 20 AND 30;


4. 
DELETE FROM employee
WHERE name LIKE 'C%';

DELETE FROM employee
WHERE email NOT LIKE '%@%'

DELETE FROM employee
WHERE birthday BETWEEN '1996-01-01' AND '1999-01-01'

DELETE FROM employee
WHERE id BETWEEN 5 AND 10;

DELETE FROM employee
WHERE name LIKE 'goo%';