# 🛠 Esquema Conceitual – Oficina Mecânica

## 📘 Descrição do Projeto

Este projeto representa o esquema conceitual de um sistema de gerenciamento de ordens de serviço em uma **oficina mecânica**. O sistema cobre as interações entre **clientes**, **veículos**, **equipes de mecânicos**, **serviços** prestados e **peças** utilizadas. A proposta é permitir controle completo do ciclo de atendimento do cliente, desde o registro do veículo até a emissão e execução de ordens de serviço (OS).

O modelo foi criado com base em uma narrativa proposta para fins educacionais.

## 🧱 Entidades Principais

- Cliente
- Veículo
- Ordem de Serviço (OS)
- Equipe
- Mecânico
- Serviço
- Peça

## 🔄 Relacionamentos

- Um cliente pode possuir vários veículos.
- Um veículo pode ter várias OS.
- Uma OS é executada por uma equipe.
- Uma equipe é composta por mecânicos.
- Cada OS contém serviços e peças, com quantidade específica.

## ❗ Suposições

- Considera-se que uma OS pode ser autorizada ou não, atributo representado por um campo booleano.
- O valor total da OS é calculado com base na soma da mão de obra e peças utilizadas.
- O relacionamento entre equipe e mecânico é do tipo 1:N.

## 🖼 Diagrama ER

Veja o diagrama completo no arquivo `modelo-conceitual.png`.

## 📂 Como visualizar

Você pode visualizar o modelo conceitual utilizando ferramentas como:
- dbdiagram.io
- Lucidchart
- Draw.io (diagrams.net)

