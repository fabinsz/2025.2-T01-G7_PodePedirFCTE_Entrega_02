# Diagrama de Colaboração

## Introdução

O diagrama de sequência é um tipo de diagrama da UML (Unified Modeling Language) utilizado para representar a interação entre objetos em um determinado cenário de uso do sistema. Ele mostra a ordem em que as mensagens são trocadas e como os objetos colaboram para realizar uma funcionalidade específica.  

Esse diagrama é muito útil para compreender o **fluxo de execução**, evidenciando a sequência temporal das interações.


## Diagrama

### Componentes do Diagrama

| **Nome do Componente** | **Significado** | **Representação** |
| :--------------------- | : ------------- | : --------------- |
|  |  | |

## Aplicação no projeto

O diagrama de colaboração foi criado pensando em algumas das interações que serão necessárias no projeto PodePedirFCTE.

### Interação Fazer Pedido
![Diagrama de colaboração do projeto PodePedirFCTE](../../assets/Diagrama%20de%20Colaboração-fazer-pedidos.jpg)
<div align="center">
<strong>Figura 1</strong> – Interação Fazer Pedido - <a href="https://github.com/anabborges">Ana Clara</a>
</div>

A interação Fazer Pedido conta com os seguintes componentes:
- **:Comprador**: O usuário que está fazendo o pedido.

- **:Interface do Comprador**: A aplicação frontend no dispositivo do comprador.

- **:Servidor do Aplicativo**: O sistema backend que processa toda a lógica.

- **:Banco de Dados**: Armazena todos os dados persistentes (usuários, pedidos, restaurantes, itens).

- **:Sistema de Pagamento**: Serviço externo para processar transações financeiras.

- **:Interface do Fornecedor**: A aplicação frontend usada pelo restaurante para gerenciar pedidos.

- **:Interface do Entregador**: A aplicação frontend usada pelo motorista de entrega.


![Diagrama de colaboração do projeto PodePedirFCTE](../assets/#)
<div align="center">
<strong>Figura 1</strong> – Diagrama de colaboração do projeto PodePedirFCTE.
</div>

## Referências Bibliográficas

> FAKHROUTDINOV, Klirill. UML Communication Diagrams Overview. **uml-diagrams.org**, 2009. Disponível em: https://www.uml-diagrams.org/communication-diagrams.html. **Acesso em 20 set. 2025.**

> IBM. Communication diagrams. **IBM Developer**, fev.2023. Disponivel em: https://www.ibm.com/docs/en/dma?topic=diagrams-communication. **Acesso em: 20 set. 2025.**

> 

---

## Histórico de Versões

| **Data**       | **Versão** | **Descrição**                         | **Autor**                                      | **Revisor**                                      | **Data da Revisão** |
| :--------: | :----: | :-------------------------------- | :----------------------------------------: | :----------------------------------------: | :-------------: |
| 20/09/2025 |  `1.0`   | Criação da página do diagrama de colaboração. | [`@Willian`](https://github.com/Wooo589) | [`@Ana Clara`](https://github.com/anabborges) |   21/09/2025    |
| 21/09/2025 |  `1.1`   | Adiciona Interação Fazer Pedido. | [`@Ana Clara`](https://github.com/anabborges) | [`@`](https://github.com/) |   00/00/0000    |