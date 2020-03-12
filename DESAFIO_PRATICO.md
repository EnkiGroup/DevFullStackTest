# Introdução

As informações abaixo são necessárias para que você desenvolva e complete o desafio da melhor maneira possível.

## Instruções

* Deve-se utilizar obrigatoriamente a linguagem C# para realização do desafio.
* Utilizar qualquer meio de persistência em disco:
  * Arquivo em disco
  * Banco Relacional
  * Banco Não relacional
* É permitida a consulta à internet e utilização de frameworks adicionais de preferência na implementação.
* Espera-se que o candidato entregue uma solução funcional e bem organizada, com código limpo e de fácil entendimento.
* Pedimos que seja priorizada a funcionalidade do projeto em detrimento de sua interface gráfica / layout.
* Ao concluir nos retornar o link para o código do projeto no e-mail que enviamos o link para o desafio.

### 1 - O que esperamos?  ;-)

* Um sistema funcional.
* Com instruções para preparar o ambiente e executar.

### 2 - Enunciado principal

Deveremos criar um sistema de registro de recados que a partir de uma regra específica deva permitir relacionar os recados com os existentes.

### 3. Estrutura

O recado é composto pela seguinte estrutura:

    Recado:
        De
        Para
        Assunto
        Mensagem
        Data do recado
        Agrupado com

### 4. Regra de agrupamento

As regras para agrupar recados são:

* Somente agrupa com recados recebidos a menos de 6 meses.
* Recados do mesmo remetente (De).
* Que o assunto seja igual relacionado.
  * São considerados assuntos relacionados quando o assunto é o mesmo do outro recado, porém começa com:
    * referente:
    * respondendo:
    * complementando:

### 5. Telas

Esta estrutura é composta por 2 telas, sendo:

1. Cadastro do recado

![Tela de cadastro de recados](CadastroRecado.PNG "Tela de cadastro de recados.")

2. Listagem dos recados cadastrados

![Tela de listagem de recados](ListagemRecado.PNG "Tela de listagem de recados")

### 6 - O que vamos avaliar

* Organização do projeto
* Utilização de boas práticas e padrões arquiteturais
* Clareza do código
* Ausência de bugs
* Detalhes de UI

## Dúvidas

Entre em contato pelo e-mail vagas[arroba]encontact.com.br