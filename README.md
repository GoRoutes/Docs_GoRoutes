[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=022840&size=35&center=true&vCenter=true&width=1000&lines=Go+Routes,+The+Best+App+Of+Manage+Routes)](https://git.io/typing-svg)

---

## Membros:

<div align="center">
<table>
<tr>
<td align="center">
   <b>Anthony Loche Dos Reis</b> <br>
   <a href="https://github.com/AnthonyLoche"><img src="https://avatars.githubusercontent.com/u/126203565?v=4" width="80px;" alt="Anthony"/></a>
   <br>
   <a href="https://github.com/AnthonyLoche"><img src="https://raw.githubusercontent.com/GoRoutes/Docs_GoRoutes/refs/heads/main/images/github-logo-white.png" width="25px;" alt="GitHub"/></a>
</td>
<td align="center">
   <b>Jonatas Silva Peraza</b> <br>
   <a href="https://github.com/jonatasperaza"><img src="https://avatars.githubusercontent.com/u/73970519?v=4" width="80px;" alt="Jonatas"/></a>
   <br>
   <a href="https://github.com/jonatasperaza"><img src="https://raw.githubusercontent.com/GoRoutes/Docs_GoRoutes/refs/heads/main/images/github-logo-white.png" width="25px;" alt="GitHub"/></a>
</td>
<td align="center">
   <b>Pedro Henrique Malaquias</b> <br>
   <a href="https://github.com/PedroHenmalaquias"><img src="https://avatars.githubusercontent.com/u/127138118?v=4" width="80px;" alt="Pedro"/></a>
   <br>
   <a href="https://github.com/PedroHenmalaquias"><img src="https://raw.githubusercontent.com/GoRoutes/Docs_GoRoutes/refs/heads/main/images/github-logo-white.png" width="25px;" alt="GitHub"/></a>
</td>
</tr>
</table>
</div>

---

## 🛠 Tecnologias Utilizadas:

- **Linguagens**: ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
- **Frontend**: ![VueJs](https://img.shields.io/badge/-Vuejs-3FB17F?logo=vue&logoColor=black)
- **Backend**: ![Django](https://img.shields.io/badge/-Django-092E20?logo=django&logoColor=white)
- **Ferramentas**: ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github)

---

# Projeto Integrador - Modelo

_GoRoutes_

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

> Após dialogarmos com administradores de diversas empresas de transporte escolar, identificamos que o gerenciamento manual das rotas frequentemente se revela um processo moroso e ineficiente, especialmente quando há um grande número de alunos a serem atendidos. Diante desse cenário, nosso sistema foi concebido com o propósito de otimizar essa gestão, oferecendo um serviço automatizado de planejamento de rotas. A solução permite que a empresa insira os endereços dos alunos, bem como os pontos de partida e destino, para então calcular a rota mais eficiente. Além disso, o sistema realiza a distribuição estratégica dos alunos entre diferentes veículos, agrupando aqueles cujos trajetos apresentam maior similaridade.

Professor: [Marco André Mendes](github.com/marcoandre)

## 🛠 Links:

- 🚀 **BackEnd**: [GoRoutes_BackEnd](https://github.com/GoRoutes/GoRoutes_BackEnd)
- 🎨 **FrontEnd**: [GoRoutes_FrontEnd](https://github.com/GoRoutes/GoRoutes_FrontEnd)
- 📄 **Docs**: [Docs_GoRoutes](https://github.com/GoRoutes/Docs_GoRoutes)
- 🎨 ✏️ **Figma**: [GoRoutes Design](https://www.figma.com/design/Pm53DckyC128A7oBmkp6RP/GoRoutes?node-id=0-1&p=f&t=4rlqR8FZlcixSg3n-0)

---

# 1. Desenvolvimento:

**Serviço de Rotas**

**Gerenciamento de Rotas Sobre Transporte de Passageiros**

A empresa escolhida foi a **Sul Turismo**, uma empresa de tranporte de passageiros tanto para turismo quanto transporte escolar;
O aplicativo em si foca em algumas coisa, como pontos podemos citar, o rastreamento por parte da empresa e clientes de seu tranporte, ou o transporte de algum familiar, uma boa comunicação, avisar aos motoristas para onde quer ir, avisar os horarios que ele quer retornar ou ir, e um gerenciamento das rotas por parte dos motoristas;

---

# 2. Situação Problema:

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")


- A empresa escolhida foi a **Sul Turismo**, uma empresa de transportes escolares e para turismo também, o dono é o `Seu Antonio`, e de funcinários temos vários, como motoristas podemos citar [Edimar, Alexander, Borba, Marcos, Edivaldo] entre outros;
- A empresa em si nao tem casos e situações complexas. Um cliente, contacta a empresa com o fim de saber valores, planos, portabilidade, e tudo relacionado a isso. A empresa responde e caso seja favorável à ambos, um contrato é fechado, seja por um número `X` de memes por um valor `N`. Durante o fechamento do contrato é acertado lugar onde o cliente mora, onde deseja ser levado, hórarios, e possiveis eventos que mudem isto, e possiveis outros locais para ser pego ou deixado;
- A principal funcao é trazer acessiblidade e facilidade para ambas as partes, tanto para empresa quanto para o cliente, onde a empresa terá uma interface facil para gerenciar, criar, ver rotas e clientes, e para o cliente poder dizer à empresa quando voltará, onde desce, e etc, dados relacionados as rotas diarias.

---

# 3. Descrição da proposta:

**Alguns pontos importantes a se destacar são:**

- **Qual o foco de ação do software**: Os dois principais focos sao 3 funcionalidades, `1º`-Permitir os motoristas selecionar os alunos que irão fazer parte da rota e com base nisso, o sistema traça o melhor caminho baseado na distancia entre os pontos de entrega, `2º`-Permitir os clientes ver onde seu transporte está e quanto tempo demora à chegar, `3º`- Permitir com que os clientes facilmente informem se voltarão na remessa de meio dia ou da cinco horas;
- **Os níveis de usuário do sistema**. Haverá 3 tipos de usuarios, os motoristas, que terão permissao de admins sobre o sistema, os clientes, e caso o cliente em si for de menor, haverá um cadastro a mais de seu responsavel como um login;
- **O que poderá ser feito no software**: Admins-Gerenciar veiculos, clientes, rotas, e etc / Clientes-Comunicar com a empresa e ver dados.

`ESPECIFICAR DIFERENÇA DE USUARIOS USANDO UMA TABELA PRA ISSO`

---

# 4. Regras de negócio

**Regras para a criação de regras de negócio**

De maneira geral, as regras de negócio devem:

- Ser **simples**, isto é, ter apenas uma função.
- Ser **completas**, com início, meio e fim.
- Ser possíveis de **mensurar** e **rastrear**.
- Estar em consonância com a **legislação**.
- Estar **atualizadas** e sempre **revisadas**.
- Refletir a **política** e os **valores** da organização.
- Ser **inteligíveis** para os colaboradores e envolvidos no processo.

**4.4 Exemplos de regras de negócio**

- Em um controle de qualidade de granja, pode-se dizer que a cada 100 ovos impróprios para consumo, o lote será descartado.
- Em um banco, clientes com faturamento mensal de mais de R$ 25 mil e CPF sem restrições, serão atendidos pelo gerente Premium pessoa física.
- Para conclusão de licitações, devem ser feitos três orçamentos e o vencedor será sempre o de menor preço final.
- Em um processo de seleção de RH, o candidato só pode ser aprovado se tiver mais de 5 anos de experiência na área, diploma de pós-graduação, espanhol fluente e pretensão salarial abaixo de R$ 8.000,00.
- Em um processo de vendas, o vendedor só pode vender um produto se o cliente tiver mais de 18 anos, renda familiar acima de R$ 5.000,00 e não tiver restrições no CPF.
- Em um processo de compras, o fornecedor só pode ser contratado se tiver nota fiscal, certificado de qualidade e preço abaixo de R$ 10,00 por unidade.
- Em um processo de logística, o pedido só pode ser enviado se o cliente tiver mais de 18 anos, endereço de entrega no mesmo estado e não tiver restrições no CPF.

**4.5 Como escrever regras de negócio?**

- Número identificador.
- Nome da regra.
- Data de criação e data da última alteração para comparações e controle.
- Nome dos Autores das versões.
- Número da versão (1, 2 etc).
- Dependências: insira o identificador das regras atreladas, às quais a regra em questão depende.
- Uma descrição detalhada para compreensão da regra.

**4.6 Regras de Negócio com Formatação**

- **RN01 – TITULO**: ;
- **RN02 – TITULO**: ;
- **RN03 – TITULO**: ;
- **RN04 – TITULO**: ;
- **RN05 – TITULO**: ;
- **RN06 – TITULO**: ;
- **RN07 – TITULO**: ;
- **RN08 – TITULO**: ;
- **RN09 – TITULO**: ;
- **RN10 – TITULO**: ;
- **RN11 – TITULO**: ;
- **RN12 – TITULO**: ;
- **RN13 – TITULO**: ;
- **RN14 – TITULO**: ;
- **RN15 – TITULO**: ;

<!-- <img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=022840&height=120&section=footer"/> -->
