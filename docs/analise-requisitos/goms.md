# GOMS (Goals, Operators, Methods, And Selection Rules)

## Introdução 
O GOMS é um método para descrever uma tarefa e o conhecimento do usuário sobre
como realizá-la em termos de objetivos (goals), operadores (operators), métodos (methods)
e regras de seleção (selection rules).

 - Os objetivos representam o que o usuário quer realizar utilizando o software
 - Operadores: são as ações cognitivas ou físicas que o sistema permite que o usuário execute, como inserir dados via teclado.
 - Os métodos são sequências bem conhecidas de sub-objetivos e operadores que permitem atingir um objetivo maior.
 - Regras de exceção: Referem-se a tomada de decisão por parte do usuário diante da possibilidade de possuir mais de um método.


## Funcionalidades Avaliadas pela GOMS
     Tabela que monstra quais funcionalidades foram avaliadas pela HTA

<center>

**Tabela 1** - Funcionalidades avaliadas

 Funcionalidade    |    Integrante Responsável             |  
|:------:|:-------------------------------:|
| [2ª via de pagamento](#segunda-via-de-pagamento) | Dara  |  
| [Unidades cadastradas](#unidades-cadastradas) | Davi |
| [Agendar visita técnica](#agendar-visita-técnica) | Henrique  |


_Fonte: Davi Casseb_

**Figura 1*- Página inicial da Agência Virtual da Neoenergia.

![Página inicial da agência](../../assets/neoenergia_1.jpeg){ width="900px" }

 _Fonte: Site da agência virtual_  

</center>

### Segunda via de pagamento 

#### Introdução 

No site da agência virtual da Neoenergia forma escolhidas algumas funcionalidades, entre elas a de visualização, pesquisa e geração de segunda via de _Boletos_. [Dara Maria](https://github.com/daramariabs) foi escolhida como responsável por essa funcionalidade. 

```
Goal 1: Listar todas as funcionalidades da agência virtual
    Method 1: Inserir dados - deixar os espaços sem preencher.
    Method 2: Inserir os dados incorretamente.
Goal 2: Procurar um cadastro específico
    Method 1: Ir até o endereço da Agência Virtual (ou real ou eletrônico) e informar os seguintes dados
        Operation 1: Informar nome a ser buscado
        Operation 2: Informar o CPF
        Operation 3: Informar CEP (opcional)
        Operation 4: Informar região (opcional)
        Operation 5: submeter dados
```
<center>

**Figura 2*- Página para requerimento da segunda via do boleto.

![Página de segunda via da agência](../../assets/neoenergia_4.jpeg){ width="900px" }

_Fonte: Site da agência virtual_

</center>

### Unidades cadastradas
Nessa tarefa o usuário pretende solicitar todas as unidades cadastradas em seu CPF, foi analisada pelo integrante [Davi Casseb](https://github.com/dcasseb). Primeiro na página como mostra na Figura 3, em seguida pede-se o código do cliente e o código da UC como mostrada na Figura.

<center>

**Figura 3*- Página para requerimento das unidades cadastradas no CPF.

![Página de consulta de unidades consumidoras](../../assets/neoenergia_3.jpeg){ width="900px" }

_Fonte: Site da agência virtual_ 

</center>

```
GOAL 0: Descobrir se a pessoa possui unidades cadastradas.
  GOAL 1: Solicitar os imóveis cadastrados em seu CPF.
    METHOD 1.A: Acessar o sistema de solicitação da agência virtual.
    (SEL. RULE: O usuário possui acesso ao sistema e sabe como navegar nele.)
    METHOD 1.B: Entrar em contato com a Neoenergia por telefone ou e-mail para obter instruções sobre como solicitar os registros em seu CPF.
    (SEL.RULE: O usuário não está familiarizado com o sistema online ou não possui acesso a ele.)
  GOAL 2: Preencher corretamente os dados necessários para a solicitação de unidades cadastradas.
    METHOD 2.A: Inserir os dados pessoais da pessoa para quem os registros estão sendo solicitados.
    (SEL. RULE: O usuário possui os dados pessoais da pessoa.)
      OP. 2.A.1: Digitar o nome completo da pessoa.
      OP. 2.A.2: Preencher o CPF (Cadastro de Pessoa Física) da pessoa.
      OP. 2.A.3: Fornecer o RG (Registro Geral) da pessoa.
      OP. 2.A.4: Se aplicável, inserir a data de nascimento da pessoa.
      OP. 2.A.5: Inserir o endereço residencial completo da pessoa.
      OP. 2.A.6: Se aplicável, incluir o endereço comercial completo da pessoa.
      OP. 2.A.7: Indicar o CEP (Código de Endereçamento Postal) tanto do endereço residencial quanto do endereço comercial.
    METHOD 2.B: Revisar os dados fornecidos para garantir que estejam corretos e completos.
    (SEL. RULE: O usuário deseja evitar erros na solicitação.)
      OP. 2.B.1: Verificar se todos os campos foram preenchidos corretamente.
      OP. 2.B.2: Revisar se não há erros de digitação nos dados fornecidos.
      OP. 2.B.3: Confirmar se os dados estão atualizados e correspondem à pessoa correta.
      OP. 2.B.4: Corrigir qualquer informação incorreta ou incompleta identificada durante a revisão.
  GOAL 3: Confirmar o envio da solicitação.
    METHOD 3.A: Enviar a solicitação através do sistema online e aguardar a confirmação.
    (SEL. RULE: O usuário tem acesso à internet e confia na eficácia do sistema.)
    METHOD 3.B: Entrar em contato com a Neoenergia para confirmar o recebimento da solicitação.
    (SEL. RULE: O usuário prefere confirmar pessoalmente.)
  GOAL 4: Receber um código de acompanhamento da solicitação.
    METHOD 4.A: Aguardar o recebimento do código de acompanhamento através do e-mail fornecido na solicitação.
    (SEL. RULE: O usuário confia na eficácia do sistema de envio de e-mails.)
    METHOD 4.B: Entrar em contato com a Neoenergia para solicitar o código de acompanhamento, caso não seja recebido dentro do prazo esperado.
    (SEL.RULE: O usuário prefere confirmar pessoalmente.)
```

###  Agendar visita técnica

A tarefa analisada pelo [Henrique Alencar](https://github.com/henryqma) foi o agendamento de visita técnica. O objetivo dessa tarefa é que o usuário consiga realizar, verificar, editar ou cancelar o agendamento da visita de um técnico na sua residência.

```

GOAL 0: Agendar visita técnica
  OP 1: Acessar o site da Neoenergia
  OP 2: Realizar login
  OP 3: Selecionar unidade cadastrada
  OP 4: Acessar função de agendamento
  GOAL 1: Solicitar visita
    OP 1: Solicitar novo agendamento
    OP 2: Informar problema
    OP 3: Selecionar data
    OP 4: Selecionar horário
    OP 5: Confirmar agendamento 
  GOAL 2: Alterar data de visita técnica
    OP 1: Selecionar agendamento
    OP 2: Alterar data
    OP 3: Alterar horário
    OP 4: Confirmar agendamento
  GOAL 3: Cancelar Agendamento
    OP 1: Selecionar Agendamento
    OP 2: Confirmar cancelamento

```

## Bibliografia
> BARBOSA, S.D.J.; SILVA, B.S. Interação Humano-Computador. Editora Campus-Elsevier, 2010.

## Referências bibliograficas

> Agência virtual da Neoenergia. Neoenergia. Disponível em: [https://agenciavirtual.neoenergiabrasilia.com.br/](https://agenciavirtual.neoenergiabrasilia.com.br/). Acesso em: 02 dez 2024.


## Histórico de versão

| Versão | Data       | Descrição                             | Autor(es)                                       | Revisor(es)             |
| ------ | ---------- | ------------------------------------- | ----------------------------------------------- | ----------------------- |
| `1.0`  | 03/12/2024 | Criação do documento                    | [Davi Casseb](https://github.com/dcasseb), [Henrique Alencar](https://github.com/henryqma), [Dara Maria](https://github.com/daramariabs)      | Dara Maria, Davi Casseb, Henrique Alencar |
