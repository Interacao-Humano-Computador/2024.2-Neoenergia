# Introdução 
No campo da Interação Humano-Computador (IHC), diretrizes frequentemente adotadas incluem alinhar-se às expectativas dos usuários, simplificar as atividades, equilibrar o controle e a liberdade oferecidos ao usuário, manter padrões de consistência, priorizar a eficiência, antecipar as necessidades do público-alvo, garantir visibilidade e reconhecimento, oferecer conteúdos úteis e adequadamente apresentados, além de projetar o sistema para minimizar erros. Tais princípios são fundamentais para criar interfaces e interações mais eficazes.

Norman (1988) destaca a relevância de desenvolver sistemas baseados em um modelo conceitual bem definido e de fácil compreensão para os usuários. Esse modelo deve permitir que eles compreendam como as ações realizadas e as informações do sistema se conectam ao conhecimento que possuem sobre o mundo. Ele sublinha que o design deve favorecer a identificação das ações possíveis em cada situação, tornar os elementos do sistema visíveis, facilitar a avaliação de seu estado atual e alinhar as intenções dos usuários com as ações e seus resultados, seguindo mapeamentos intuitivos.

## Objetivo
Esse artefato tem como objetivo verificar os princípios gerais e se a agência virtual da Neoenergia viola estes princípios e, caso viole, sugerir uma melhoria.

## Metodologia 
Para analisarmos os princípios gerais, realizamos uma análise individual de violações que o site poderia ter em relação ao Princípio.

# Correspondência com as Expectativas dos Usuários

### Motivação
Conforme Nielsen (1994), é fundamental que o projetista adote convenções alinhadas ao mundo real, organizando as informações de forma lógica e em uma sequência que faça sentido para os usuários. Por isso, é crucial compreender os padrões de ações que lhes são familiares. Caso a solução proposta se desvie dessas familiaridades, deve ao menos apresentar uma estrutura lógica que seja compreensível. Além disso, ao término de cada tarefa, o sistema precisa fornecer um feedback claro, permitindo ao usuário concluir a atividade com tranquilidade e seguir para outras tarefas.

Para atender às expectativas dos usuários, é indispensável desenvolver sistemas que utilizem mapeamentos naturais, facilitando a compreensão das conexões entre suas intenções, as ações disponíveis e os resultados obtidos.

### Violação
A violação que vemos na página principal do site da agência virtual da Neoenergia, é que mesmo selecionando o serviço a ser requisitado, o usuário não é levado à página desejada, mesmo que o usuário já tenha feito _login_. Como mostra na figura 1

<center>

**Figura 1** - Violação da Correspondência com as Expectativas dos Usuários

![Página Inicial](../assets/neoenergia_2.jpeg)
_Fonte: Site Agência Virtual da Neoenergia_

</center>

### Sugestão de melhoria

Podemos realizar algumas melhorias para atender a Correspondência dos usuários como:

- Responsividade do site. O site deverá levar o usuário para o serviço que ele deseja, sem a necessidade de inserir múltiplas vezes seus dados.
- Verificar o layout do site para que possa ser repensado as informações, de maneira que fiquem mais intuitivas.

# Antecipação

### Motivação
Diante do desafio de desenvolver aplicações que transcendam a mera resposta às necessidades imediatas dos usuários, somos convocados a abraçar o princípio da antecipação. Em vez de esperar passivamente por comandos, devemos aspirar a prever as necessidades e desejos dos usuários, fornecendo-lhes as informações e ferramentas necessárias antes mesmo que eles as solicitem.

Cooper(1999) e Tognazzini(2003) nos guiam nessa jornada, lembrando-nos de que o verdadeiro valor de uma aplicação reside em sua capacidade de tomar a iniciativa, oferecendo não apenas respostas diretas, mas também informações adicionais pertinentes. Imagine um software que, ao ser questionado sobre um restaurante, não apenas fornece seu número de telefone, mas também seus horários de funcionamento. Este é o nível de antecipação que devemos almejar.

Não basta apenas antecipar as necessidades; é crucial também oferecer configurações padrão cuidadosamente pensadas. Os valores padrão devem ser escolhidos com sabedoria, sendo facilmente ajustáveis pelos usuários conforme a situação exige. Lembre-se, as pessoas tendem a aceitar os valores padrão como corretos, então cada escolha deve ser feita com atenção e consideração.

Portanto, diante de cada linha de código, cada configuração de interface, devemos nos perguntar: estamos verdadeiramente antecipando as necessidades dos nossos usuários? Estamos facilitando suas interações de forma proativa? Sejamos arquitetos da antecipação, construindo não apenas software, mas sim experiências que superam expectativas e proporcionam um serviço excepcional.

### Violação
Como explicado acima, o site da Agência Virtual da Neoenergia não possui nenhuma informação para onde o usário deve ir, ou proceder para, por exemplo atualizar seu cadastro. Na figura 3 monstramos o layout do site, monstrando que o site não oferece as informações ao usuário.

<center>

**Figura 3** - Antecipação

![Página de solicitação de Unidades Cadastradas](../assets/neoenergia_3(corrigido).jpeg)

_Fonte: Site Agência Virtual da Neoenergia_

</center>

## Sugestão de melhoria
Para resolver a violação de antecipação e melhorar a experiência do usuário, sugerimos a implementação de um sistema de mensagens de informações de acesso. Ao entrar na plataforma, os usuários seriam direcionados a uma página de login, onde poderiam inserir suas credenciais e receberiam uma mensagem informando para onde o usuário deveria ir para receber determinado serviço. Com isso, o site poderia antecipar as necessidades dos usuários, proporcionando uma experiência mais fluida e eficiente. Essa abordagem não só melhoraria a eficiência do site, como também criaria uma experiência de usuário mais satisfatória e personalizada, alinhada com os princípios de IHC de antecipação e proatividade.

# Visibilidade e Reconhecimento

### Motivação
No processo de desenvolvimento e design de interfaces, é comum perder o foco no elemento mais importante: os usuários. Por isso, é essencial garantir que não apenas as funcionalidades estejam evidentes, mas também as intenções e os estados do sistema. Norman destaca a necessidade de reduzir momentos de incerteza, deixando claro para os usuários o que pode ser feito e como realizar essas ações. A interface deve funcionar como uma extensão intuitiva de suas intenções, apresentando opções relevantes para o contexto e ocultando aquelas desnecessárias. Além disso, é fundamental oferecer feedback imediato e consistente após cada interação, alinhando-se ao modelo mental do usuário.

Autores como Nielsen (1993), Shneiderman (1998) e Tognazzini (2003) reforçam a importância da visibilidade contínua dos elementos da interface. Os usuários não devem ser deixados sem informações sobre o funcionamento do sistema. Cada interação deve ser acompanhada por um feedback adequado, cuja intensidade varia conforme a frequência e o impacto da ação. Tognazzini (2003) também apresenta orientações práticas para lidar com diferentes tempos de resposta do sistema, desde ações instantâneas até aquelas que exigem maior tempo de processamento. É fundamental manter os usuários informados e engajados, mesmo em situações de espera mais prolongada.

Portanto, ao projetar interfaces, a prioridade deve ser sempre os usuários. Eles não devem enfrentar dificuldades para entender interações anteriores ou estados ocultos do sistema. Em vez disso, é necessário fornecer indicações claras, orientar suas ações e mantê-los cientes de onde estão e do que podem fazer. Essa abordagem é essencial para criar experiências de uso envolventes e satisfatórias.

### Violação

No site móvel da Agência Virtual, , como monstrado na figura 4

<center>

**Figura 4** - Visibilidade e Reconhecimento

![Página de Usuário Móvel](../assets/neoenergiaPagUsuario_movel(corrigido).jpeg)

_Fonte: Site Agência Virtual da Neoenergia_

</center>

## Sugestão de melhoria
Para a melhoria da Visibilidade e reconhecimento recomendamos:
* Diferentes cores para os ícones;

* Modificar o contraste dos ícones para que sua visibilidade não seja afetada, prejudicando principalmente os usuários mais velhos;

* Fornecer uma visão geral do site de maneira otimizada, promovendo a eficiência em sua usabilidade.

## Principios Gerais escolhidos para o projeto:
Com base em todas as diretrizes avaliadas e nas funcionalidades escolhidas por cada integrante, os principios gerais escolhidos para o projeto são:

      1 - Correspondência com as Expectativas dos Usuários
      2 - Antecipação
      3 - Visibilidade e Reconhecimento

## Bibliografia 
> BARBOSA, Simone; SILVA, Bruno. Interação Humano Computador. 1. ed. Rio de Janeiro: Elsevier, 2010.
> Agência Virtual da Neoenergia. Disponível em: [https://agenciavirtual.neoenergia.com/](https://agenciavirtual.neoenergia.com/). Acesso em: 01 dez 2024.

## Histórico de versão

| Versão | Data       | Descrição                             | Autor(es)                                       | Revisor(es)             |
| ------ | ---------- | ------------------------------------- | ----------------------------------------------- | ----------------------- |
| `1.0`  | 03/12/2024 | Criação da página                     | [Davi Casseb](https://github.com/dcasseb)       | Dara Maria, Henrique Alencar |
| `1.1`  | 03/12/2024 | Refatoração da página                     | [Davi Casseb](https://github.com/dcasseb)       | Dara Maria, Henrique Alencar |
