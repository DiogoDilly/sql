# sql

create database AulaBancoJunto;

use AulaBancoJunto;

create table Turma1(
turma int primary key,
Alunos int not null,
Professor varchar(20) not null,
QuantidadesMaterias int not null,
LiderDeTurma varchar(20) not null
);

create table Turma2(
turma int primary key,
Alunos int not null,
Professor varchar(20) not null,
QuantidadesMaterias int not null,
LiderDeTurma varchar(20) not null
);


create table Turma3(
turma int primary key,
Alunos int not null,
Professor varchar(20) not null,
QuantidadesMaterias int not null,
LiderDeTurma varchar(20) not null
);

create table Turma4(
turma int primary key,
Alunos int not null,
Professor varchar(20) not null,
QuantidadesMaterias int not null,
LiderDeTurma varchar(20) not null
);

create table Turma5(
turma int primary key,
Alunos int not null,
Professor varchar(20) not null,
QuantidadesMaterias int not null,
LiderDeTurma varchar(20) not null
);

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,23, 'Marco', 26,'Ronaldo'); 

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,26, 'Jonathan', 12,'Carlos');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,27, 'Jonatha', 13,'Carlo');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,28, 'Jonath', 14,'Carlão');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,29, 'Jonat', 15,'Carlinhos');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,30, 'Jona', 16,'karl');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,31, 'Jon', 17,'karlos');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,32, 'Jo', 18,'karlo');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,33, 'J', 19,'Karlão');

insert into Turma1(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(111,34, 'Jonh', 20,'karlinhos');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,15, 'Mauricio', 26,'Oliver');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,19, 'Samuel', 12,'Lucas');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,20, 'Jasionel', 13,'Marcov');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,21, 'Jasione', 14,'Marciano');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,22, 'Jasion', 15,'Marcian');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,23, 'Jasio', 16,'Marcia');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,24, 'Jasi', 17,'Marci');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,25, 'Jas', 18,'Marc');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,26, 'Ja', 19,'Mar');

insert into Turma2(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(122,27, 'Jason', 20,'Marcão');



insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,34, 'Manuel', 26,'Norton');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,39, 'Sabrina', 12,'Erique');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,40, 'Sabrin', 13,'Eriqu');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,41, 'Sabri', 14,'Eriq');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,42, 'Sabr', 15,'Eri');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,43, 'Sab', 16,'Er');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,44, 'Sa', 17,'E');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,45, 'jasckson', 18,'Michael');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,46, 'jasckso', 19,'Michae');

insert into Turma3(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(133,47, 'jascks', 20,'Micha');


insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,48, 'Marcelo', 26,'Diego');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,21, 'Marcio', 12,'Paulo');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,22, 'Marcião', 13,'Paulão');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,23, 'Marciã', 14,'Paulã');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,24, 'Marci', 15,'Paul');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,25, 'Marc', 16,'Pau');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,26, 'Mar', 17,'Pa');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,27, 'Macarena', 18,'Patolino');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,28, 'Macaren', 19,'Patolin');

insert into Turma4(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(144,29, 'Macare', 20,'Patoli');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,13, 'Jenifer', 26,'Samara');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,20, 'Fernanda', 12,'Gabriel');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,21, 'Fernand', 13,'Gabrie');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,22, 'Fernan', 14,'Gabri');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,23, 'Ferna', 15,'Gabr');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,24, 'Fern', 16,'Gab');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,25, 'Fer', 17,'Ga');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,26, 'Francisco', 18,'Galeleo');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,27, 'francisc', 19,'Galele');

insert into Turma5(turma, Alunos, Professor, QuantidadesMaterias, LiderDeTurma)
values(155,20, 'Francis', 20,'Galel');

update Turma set Alunos = 'xxxxxxxxxx' where turma = 111;

update Turma set Alunos = 'xxxxxxxxx' where turma = 111;

update Turma set Alunos = 'xxxxxxxx' where turma = 111;

update Turma set Alunos = 'xxxxxxx' where turma = 111;

update Turma set Alunos = 'xxxxxx' where turma = 111;

update Turma set Alunos = 'xxxxx' where turma = 111;

update Turma set Alunos = 'xxxx' where turma = 111;

update Turma set Alunos = 'xxx' where turma = 111;

update Turma set Alunos = 'xx' where turma = 111;

update Turma set Alunos = 'x' where turma = 111;

update Turma set Alunos = 'xxxxxxxxxx' where turma = 112;

update Turma set Alunos = 'xxxxxxxxx' where turma = 112;

update Turma set Alunos = 'xxxxxxxx' where turma = 112;

update Turma set Alunos = 'xxxxxxx' where turma = 112;

update Turma set Alunos = 'xxxxxx' where turma = 112;

update Turma set Alunos = 'xxxxx' where turma = 112;

update Turma set Alunos = 'xxxx' where turma = 112;

update Turma set Alunos = 'xxx' where turma = 112;

update Turma set Alunos = 'xx' where turma = 112;

update Turma set Alunos = 'x' where turma = 112;

update Turma set Alunos = 'xxxxxxxxxx' where turma = 113;

update Turma set Alunos = 'xxxxxxxxx' where turma = 113;

update Turma set Alunos = 'xxxxxxxx' where turma = 113;

update Turma set Alunos = 'xxxxxxx' where turma = 113;

update Turma set Alunos = 'xxxxxx' where turma = 113;

update Turma set Alunos = 'xxxxx' where turma = 113;

update Turma set Alunos = 'xxxx' where turma = 113;

update Turma set Alunos = 'xxx' where turma = 113;

update Turma set Alunos = 'xx' where turma = 113;

update Turma set Alunos = 'x' where turma = 113;

update Turma set Alunos = 'xxxxxxxxxx' where turma = 114;

update Turma set Alunos = 'xxxxxxxxx' where turma = 114;

update Turma set Alunos = 'xxxxxxxx' where turma = 114;

update Turma set Alunos = 'xxxxxxx' where turma = 114;

update Turma set Alunos = 'xxxxxx' where turma = 114;

update Turma set Alunos = 'xxxxx' where turma = 114;

update Turma set Alunos = 'xxxx' where turma = 114;

update Turma set Alunos = 'xxx' where turma = 114;

update Turma set Alunos = 'xx' where turma = 114;

update Turma set Alunos = 'x' where turma = 114;

update Turma set Alunos = 'xxxxxxxxxx' where turma = 115;

update Turma set Alunos = 'xxxxxxxxx' where turma = 115;

update Turma set Alunos = 'xxxxxxxx' where turma = 115;

update Turma set Alunos = 'xxxxxxx' where turma = 115;

update Turma set Alunos = 'xxxxxx' where turma = 115;

update Turma set Alunos = 'xxxxx' where turma = 115;

update Turma set Alunos = 'xxxx' where turma = 115;

update Turma set Alunos = 'xxx' where turma = 115;

update Turma set Alunos = 'xx' where turma = 115;

update Turma set Alunos = 'x' where turma = 115;

