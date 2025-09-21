# Diagrama de Colaboração

## Introdução

O diagrama de sequência é um tipo de diagrama da UML (Unified Modeling Language) utilizado para representar a interação entre objetos em um determinado cenário de uso do sistema. Ele mostra a ordem em que as mensagens são trocadas e como os objetos colaboram para realizar uma funcionalidade específica.  

Esse diagrama é muito útil para compreender o **fluxo de execução**, evidenciando a sequência temporal das interações.

### Vantagens
- Destaca a **estrutura da interação** entre os objetos.  
- Útil para visualizar **relações organizacionais** dentro do sistema.  
- Pode complementar o diagrama de sequência, oferecendo outra perspectiva.  

### Desvantagens
- Não evidencia bem o **fator temporal** das mensagens.  
- Pode ser menos intuitivo para fluxos complexos de interação.  


## Diagrama

### Componentes do Diagrama

| **Nome do Componente** | **Significado** | **Representação** |
| :--------------------- | : ------------- | : --------------- |
| Frame | Representa o fluxo de uma interação | ![Frame](../../assets/frame.png) |
| Lifeline | Elemento nomeado que representa um participante individual na interação | ![Lifeline](../../assets/lifeline.png) |
| Message | Uma linha de expressão sequencial com uma seta que indica a direção da comunicação | ![Message](../../assets/message.png) |

## Aplicação no projeto

O diagrama de colaboração foi criado pensando em algumas das interações que serão necessárias no projeto PodePedirFCTE.

### Interação Fazer Pedido
![Diagrama de colaboração do projeto PodePedirFCTE](../../assets/Diagrama%20de%20Colaboração-fazer-pedidos.jpg)
<div align="center">
<strong>Figura 1</strong> – Interação Fazer Pedido - <a href="https://github.com/anabborges">Ana Clara</a>
</div>

A interação Fazer Pedido conta com os seguintes elementos (lifelines):
- **:Comprador**: O usuário que está fazendo o pedido.

- **:Interface do Comprador**: A aplicação frontend no dispositivo do comprador.

- **:Servidor do Aplicativo**: O sistema backend que processa toda a lógica.

- **:Banco de Dados**: Armazena todos os dados persistentes (usuários, pedidos, restaurantes, itens).

- **:Sistema de Pagamento**: Serviço externo para processar transações financeiras.

- **:Interface do Fornecedor**: A aplicação frontend usada pelo restaurante para gerenciar pedidos.

- **:Interface do Entregador**: A aplicação frontend usada pelo motorista de entrega.

### Interação Entregador
![Diagrama de colaboração do projeto PodePedirFCTE](../../assets/Diagrama%20de%20Colaboração-Entregador.png)
<div align="center">
<strong>Figura 2</strong> – Interação Entregador - Storch
</div>

A interação entregarPedido conta com as seguintes mensagens:

**1. Notificar Pedido Disponível**
- O sistema envia a notificação de um novo pedido para a interface do entregador.

**2. Aceitar Pedido**
- O entregador aceita o pedido pelo aplicativo.

**3. Confirmar Aceite**
- O sistema atribui o pedido ao entregador e confirma a ação.

**4. Atualizar Status ("Em entrega")**
- O status do pedido é atualizado para "Em entrega".

**5. Notificar Status ("Pedido em rota")**
- O comprador é notificado de que o pedido está a caminho.

**6. Confirmar Entrega**
- O entregador confirma a entrega no aplicativo.

**7. Registrar Entrega**
- O sistema registra a entrega e as evidências no banco de dados.

**8. Atualizar Status ("Entregue")**
- O status do pedido é finalizado como "Entregue".

**9. Notificar Confirmação ("Pedido entregue")**
-  O comprador e o fornecedor são notificados de que o pedido foi entregue.

**10. Liberar Repasses**
-  O sistema aciona o processo de pagamento para o entregador e o fornecedor.

## Quadro de Participações

| **Membro da equipe** | **Função** |
| :------------- | :--------- |
| [Ana Clara](https://github.com/anabborges) | Interação Fazer Pedido e Tabela de Elementos |
| [Guilherme Storch](https://github.com/storch7) | Interação de Entregar Pedido e Introdução |
| [Willian Wagner](https://github.com/Wooo589) |  |

## Referências Bibliográficas

> FAKHROUTDINOV, Klirill. UML Communication Diagrams Overview. **uml-diagrams.org**, 2009. Disponível em: https://www.uml-diagrams.org/communication-diagrams.html. **Acesso em 20 set. 2025.**

> IBM. Communication diagrams. **IBM Developer**, fev.2023. Disponivel em: https://www.ibm.com/docs/en/dma?topic=diagrams-communication. **Acesso em: 20 set. 2025.**

> OMG. UML 2.5 Specification. Disponível em: https://www.omg.org/spec/UML/2.5.  

> GOOGLE. Phase 3: Sketch. Disponível em: https://designsprintkit.withgoogle.com/methodology/phase3-sketch.  

> GUEDES, Gilleanes T. A. *UML 2: Uma abordagem prática*. 2. ed. São Paulo: Novatec, 2011.  

> LARMAN, Craig. *Utilizando UML e Padrões: uma introdução à análise e ao projeto orientados a objetos e ao desenvolvimento iterativo*. 3. ed. Porto Alegre: Bookman, 2007.  

---

## Histórico de Versões

| **Data**       | **Versão** | **Descrição**                         | **Autor**                                      | **Revisor**                                      | **Data da Revisão** |
| :--------: | :----: | :-------------------------------- | :----------------------------------------: | :----------------------------------------: | :-------------: |
| 20/09/2025 |  `1.0`   | Criação da página do diagrama de colaboração. | [`@Willian`](https://github.com/Wooo589) | [`@Ana Clara`](https://github.com/anabborges) |   21/09/2025    |
| 21/09/2025 |  `1.1`   | Adiciona Interação Fazer Pedido. | [`@Ana Clara`](https://github.com/anabborges) | [`@`](https://github.com/) |   00/00/0000    |
| 21/09/2025 |  `1.2`   | Adiciona Interação do Entregador e Introdução | [`@Guilherme Storch`](https://github.com/storch7) | [`@Ana Clara`](https://github.com/anabborges) |   00/00/0000    |
| 21/09/2025 |  `1.3`   | Adiciona Tabela de Elementos e de Contribuição. | [`@Ana Clara`](https://github.com/anabborges) | [`@`](https://github.com/) |   00/00/0000    |