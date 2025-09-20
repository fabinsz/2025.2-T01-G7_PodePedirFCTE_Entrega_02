# Diagrama de Estados

# Introdução

O diagrama de estados é um tipo de diagrama dinâmico que procura representar os diferentes estados pelos quais um objeto pode passar <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>. Assim, conforme o passar do tempo, esse objeto irá mudar de estado quando ocorrer um evento interno ou externo ao sistema <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>.

## Componentes do Diagrama de Estados

| **Nome do Componente** | **Significado** | **Representação** |
| :--------------------- | : ------------- | : --------------- |
| Estado Simples | Um estado simples é um tipo de estado que não apresenta subestados, não possui regiões ou submáquinas de estado; esse componente é representado por um retângulo de cantos arredondados com o nome do estado dentro do retângulo <a id="anchor_2" onclick="document.getElementById('REF2').scrollIntoView()" style="cursor:pointer;">[2]</a>. | <img class="card-img img-fluid rounded" src="../../DiagramasDeEstados/Componentes/estado-componente.png" title="Componente estado" width=auto> |
| Pseudoestado inicial | Um pseudoestado inicial é responsável por representar um vértice padrão que é a fonte de uma única transição para o estado padrão de um estado composto. Ele é representado por um círculo pequeno e preenchido por uma cor sólida <a id="anchor_2" onclick="document.getElementById('REF2').scrollIntoView()" style="cursor:pointer;">[2]</a>. | <img class="card-img img-fluid rounded" src="../../DiagramasDeEstados/Componentes/inicio-componente.png" title="Componente de inicio" width=auto>  |
| Estado final | O estado final representa um tipo especial de estados que é utilizado para sinalizar que aquela região envolvente está completa; se uma região envolvente estiver contida em uma máquina de estados e todas as outras regiões dessa mesma máquina de estados também estiverem completas, isso significa que toda a máquina de estados está completa <a id="anchor_2" onclick="document.getElementById('REF2').scrollIntoView()" style="cursor:pointer;">[2]</a>.| <img class="card-img img-fluid rounded" src="../../DiagramasDeEstados/Componentes/final-componente.png" title="Componente final" width=auto>  |

<font size="3">Autor: [Luiz Guilherme](https://github.com/luizfaria1989), 2025.</font>

Além desses componentes mais simples, para a conexão dos estados são utilizadas setas que mostram o fluxo dos diferentes estados além de indicar quais são os eventos que são responsáveis por ativar essa transição. A UML também permite outros componentes para a criação dos diagramas de estados, como estados compostos e pontos de decisão <a id="anchor_2" onclick="document.getElementById('REF2').scrollIntoView()" style="cursor:pointer;">[2]</a>.

# Diagramas Produzidos

Para o desenvolvimento dos diagramas de estados, foi combinado com os integrantes do grupo que seriam desenvolvidos três diagramas diferentes que mostrem como será a visualização do cliente, restaurante e entregador quando um pedido for preparado e até ser entregue ao cliente.

## Visualização do Pedido para o Cliente

<img class="card-img img-fluid rounded" src="../../DiagramasDeEstados/diagrama-de-estados-visualizacao-cliente.png" title="Diagrama de estados para a visualização do cliente" width=auto>

<div  style="text-align: center">

<font size="3">Autor: [Luiz Guilherme](https://github.com/luizfaria1989), 2025.</font>

</div>

## Visualização do Pedido para o Restaurante

<img class="card-img img-fluid rounded" src="../../DiagramasDeEstados/diagrama-de-estados-visualizacao-restaurante.png" title="Diagrama de estados para a visualização do restaurante" width=auto>

<div  style="text-align: center">

<font size="3">Autor: [João](https://github.com/Joao151104), 2025.</font>

</div>

## Visualização do Pedido para o Entregador

---

# Referência Bibliográfica

> <span id="REF1">1.</span> <a onclick="document.getElementById('anchor_1').scrollIntoView()" style="cursor:pointer;"> Arquitetura e desenho de software, aula - projeto e desenho de software. Disponivel em:</a>: https://aprender3.unb.br/pluginfile.php/3178388/mod_page/content/1/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Modelagem%20UML%20Dinâmica%20-%20Profa.%20Milene.pdf. Acesso em: 20 de setembro de 2025;

> <span id="REF2">2.</span> <a onclick="document.getElementById('anchor_11').scrollIntoView()" style="cursor:pointer;"> UML Diagrams Org. Disponível em: [https://www.uml-diagrams.org/state-machine-diagrams.html](https://www.uml-diagrams.org/state-machine-diagrams.html). Acesso em: 20 de setembro de 2025. 

---

# Histórico de Versões

| **Data**       | **Versão** | **Descrição**                         | **Autor**                                      | **Revisor**                                      | **Data da Revisão** |
| :--------: | :----: | :-------------------------------- | :----------------------------------------: | :----------------------------------------: | :-------------: |
| 20/09/2025 |  `1.0`   | Criação da página dos diagramas de estados e inserção dos primeiros diagramas. | [`@Luiz`](https://github.com/luizfaria1989) | [`@`](https://github.com/) |   00/00/0000    |