# Ödev 8

Soru1:
test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

``CREATE TABLE employee (
id SERIAL PRIMARY KEY,
name VARCHAR(50),
birtday DATE,
email VARCHAR(100)
);``

---

Soru2:
Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

``insert into employee (name, birtday, email) values ('Vivie', '1949-10-26', 'vcowdery0@un.org');
insert into employee (name, birtday, email) values ('Conrad', '1925-05-21', 'ctriswell1@zimbio.com');
insert into employee (name, birtday, email) values ('Jeremie', '1919-01-17', 'jknewstubb2@amazon.co.uk');
insert into employee (name, birtday, email) values ('Kirk', '1987-04-28', 'kstanden3@unblog.fr');
insert into employee (name, birtday, email) values ('Dolorita', '1967-06-08', 'dsushams4@nydailynews.com');
insert into employee (name, birtday, email) values ('Tonie', '1990-06-20', 'tdowsey5@shinystat.com');
insert into employee (name, birtday, email) values ('Isabeau', '2015-11-16', 'isaffe6@rediff.com');
insert into employee (name, birtday, email) values ('Roseanna', '1974-05-18', 'rklimowski7@springer.com');
insert into employee (name, birtday, email) values ('Ignaz', '1994-08-16', 'ipogson8@elegantthemes.com');
insert into employee (name, birtday, email) values ('Meridel', '1970-05-13', 'mrummins9@nhs.uk');
insert into employee (name, birtday, email) values ('Garnet', '2014-11-27', 'glawdhama@va.gov');
insert into employee (name, birtday, email) values ('Agretha', '1925-08-12', 'agwillymb@ezinearticles.com');
insert into employee (name, birtday, email) values ('Mycah', '1989-07-09', 'mshillabearc@craigslist.org');
insert into employee (name, birtday, email) values ('Eli', '1905-04-25', 'evamplewd@soundcloud.com');
insert into employee (name, birtday, email) values ('Trixy', '1981-08-10', 'tdydee@rediff.com');
insert into employee (name, birtday, email) values ('Leonidas', '1933-07-18', 'leayresf@mozilla.com');
insert into employee (name, birtday, email) values ('Hew', '1995-01-16', 'hemsong@plala.or.jp');
insert into employee (name, birtday, email) values ('Bentley', '2011-06-20', 'bfranzenh@gov.uk');
insert into employee (name, birtday, email) values ('Ephraim', '1917-04-28', 'efochsi@instagram.com');
insert into employee (name, birtday, email) values ('Rhody', '1936-03-03', 'rkubisj@google.cn');
insert into employee (name, birtday, email) values ('Albrecht', '1967-05-16', 'aconnerlyk@zdnet.com');
insert into employee (name, birtday, email) values ('Marlo', '1912-06-14', 'mpreatorl@ft.com');
insert into employee (name, birtday, email) values ('Sunshine', '1959-05-31', 'snorcottm@cam.ac.uk');
insert into employee (name, birtday, email) values ('Rusty', '1990-12-02', 'rbilln@infoseek.co.jp');
insert into employee (name, birtday, email) values ('Desmund', '1945-02-17', 'dscoularo@yellowpages.com');
insert into employee (name, birtday, email) values ('Julio', '1919-05-11', 'jbenaharonp@opera.com');
insert into employee (name, birtday, email) values ('Lusa', '1928-08-05', 'ldavydzenkoq@eepurl.com');
insert into employee (name, birtday, email) values ('Gene', '1948-03-09', 'gdrancer@ucoz.ru');
insert into employee (name, birtday, email) values ('Lauri', '2009-09-08', 'ltunaclifts@msu.edu');
insert into employee (name, birtday, email) values ('Abel', '2015-01-27', 'agiovanittit@wp.com');
insert into employee (name, birtday, email) values ('Feodor', '2000-02-17', 'fperinu@newyorker.com');
insert into employee (name, birtday, email) values ('Margie', '1910-03-20', 'mthickpennyv@google.ca');
insert into employee (name, birtday, email) values ('Marinna', '1911-06-01', 'mmclauchlinw@alexa.com');
insert into employee (name, birtday, email) values ('Damiano', '1991-04-11', 'dcrossx@ed.gov');
insert into employee (name, birtday, email) values ('Taddeusz', '2011-01-12', 'tcorlessy@imgur.com');
insert into employee (name, birtday, email) values ('Nancie', '1914-08-04', 'nmooneyz@indiegogo.com');
insert into employee (name, birtday, email) values ('Anderea', '1926-08-10', 'ahillen10@upenn.edu');
insert into employee (name, birtday, email) values ('Cozmo', '1927-05-24', 'chadrill11@washington.edu');
insert into employee (name, birtday, email) values ('Krissy', '1932-09-08', 'kedelston12@jimdo.com');
insert into employee (name, birtday, email) values ('Pauletta', '2006-10-12', 'pledeker13@ihg.com');
insert into employee (name, birtday, email) values ('Pavia', '1951-09-22', 'pcanellas14@g.co');
insert into employee (name, birtday, email) values ('Jacinthe', '1962-01-11', 'jgoodhay15@who.int');
insert into employee (name, birtday, email) values ('Eleanor', '1987-11-28', 'egreenshields16@dyndns.org');
insert into employee (name, birtday, email) values ('Tony', '1913-05-04', 'tfarrants17@quantcast.com');
insert into employee (name, birtday, email) values ('Thorndike', '1994-12-24', 'tmourge18@domainmarket.com');
insert into employee (name, birtday, email) values ('Dominik', '1978-12-28', 'dbarczewski19@cnbc.com');
insert into employee (name, birtday, email) values ('Anthia', '1950-10-03', 'agarden1a@narod.ru');
insert into employee (name, birtday, email) values ('Rosabella', '1954-07-03', 'rscading1b@army.mil');
insert into employee (name, birtday, email) values ('Domini', '2023-12-16', 'dhumby1c@java.com');
insert into employee (name, birtday, email) values ('Klemens', '1955-09-27', 'klanchbury1d@si.edu');``

---

Soru3:
Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

``UPDATE employee
SET email = 'XXXXX'
WHERE name ='Vivie'
RETURNING *; ``

``UPDATE employee
SET name = 'YYYYY'
WHERE email ='ctriswell1@zimbio.com'
RETURNING *; ``

``UPDATE employee
SET birtday = '1900-01-01'
WHERE id = 3
RETURNING *; ``

``UPDATE employee
SET name ='ZZZZZ'
WHERE birtday = '1990-06-20'
RETURNING *; ``

``UPDATE employee
SET name = 'Arda',
birtday = '1999-09-09',
email = 'arda@edu.com'
WHERE id = 14
RETURNING *; ``

---

Soru4:
Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

``DELETE FROM employee
WHERE id = 2
RETURNING *;``

``DELETE FROM employee
WHERE name = 'Kirk'
RETURNING *;``

``DELETE FROM employee
WHERE birtday = '1990-06-20'
RETURNING *;``

``DELETE FROM employee
WHERE email = 'XXXXX'
RETURNING *;``

``DELETE FROM employee
WHERE id = 99
RETURNING *;``



---