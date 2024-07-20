Spring Data JPA | Curso 2024



https://youtu.be/Ca30sv9EbLo

JPA COM SPRING
MICHELLI BRITO

// para popular tabela com o mysql workbench
insert into tb_publisher values(uuid_to_bin(uuid()),'Alta Books');
insert into tb_publisher values(uuid_to_bin(uuid()),'Pearson');

insert into tb_author values(uuid_to_bin(uuid()),'Eric Evans');
insert into tb_author values(uuid_to_bin(uuid()),'Paul Deitel');
insert into tb_author values(uuid_to_bin(uuid()),'Marvey Deitel');

// para ver o id bin->uuid
SELECT bin_to_uuid(id),name FROM `bookstore-jpa`.tb_publisher;

SELECT bin_to_uuid(book_id),bin_to_uuid(author_id) FROM `bookstore-jpa`.tb_book_author;
