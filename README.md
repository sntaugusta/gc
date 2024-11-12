# Lower Third Sara Nossa Terra

## Descrição

- Sem necessidade de instalação de plugins.
- Simplecidade na instalação.
- Facilidade para alterar dados.

Fonte para adicionar Lower Third para lives no OBS da Sara Nossa Terra. Uma Fonte que simplifica a mudanças de nomes dos pregadores e descrições das lives através das queries strings da URL.

## Exemplo

![image](./img/lower-third-sample.gif)

[Exemplo online](https://sntaugusta.github.io/lower-third/?name=Bp.%20Christiano%20Guimar%C3%A3es&description=@bispochristiano)

## Modo de instalação

1. Crie uma nova Fonte de "Navegador"
2. Adicione um nome de sua preferência para a criar o Lower Third
3. Acesse as Propriedades de Navegador da fonte criada
4. Adicione no campo URL, a URL do git pages do lower third com as propriedades `name` e `description` na query string (Ex.: `https://sntaugusta.github.io/lower-third/?name=Bp. Christiano Guimarães&description=@sntoficial`)
5. Adicione na Largura o valor de `1920`
6. Adicione na Altura o valor de `190`
7. Pronto 🙌

### Informações extras

- O parâmetro `description` não é um parâmetro obrigatório
- Para adicionar mais nomes e descrições, adicione mais query string com a propriedade `name` (Ex.: `https://sntaugusta.github.io/lower-third/?name=Bp. Christiano Guimarães&description=@bispochristiano&name=Bpa. Camille Falcão&description=@bpacamille`)

## Em breve

- Criação de template para o arena
- Criação de template customizaveis para eventos

## Novas solicitações

Crie uma [nova issue](https://github.com/sntaugusta/lower-third/issues/new) neste repositório, e aguarde um feedback do time de desenvolvimento da Sara Nossa Terra Augusta
