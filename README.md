# Desafio-3 - STI-UFF
Projeto desenvolvido para o desafio 3 do processo seletivo da Superintendência de Tecnologia da Informação da UFF.
https://github.com/sti-uff/trabalhe-conosco/blob/master/Desafios.md

Feito em java SpringBoot e React + TypeScript, o desafio consiste em ler um CSV do disco e retornar
o CR de todos os alunos e o CR médio por curso.

Para rodar em seu computador, é necessário criar um schema no MySQL
com o mesmo nome descrito no application.properties na parte de:

spring.datasource.url=jdbc:mysql://localhost:3306/Nome Do seu Schema

além de também colocar o username e password do seu banco de dados MySQL
spring.datasource.username=Seu Usuario
spring.datasource.password=Sua senha

A url para rodar o front é : http://localhost:5173/
caso dê algum problema com portas já usadas
