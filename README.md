# Meu Pet — urgência, copy de vendas e resultados das alunas (versão 3)

Esta versão mantém a estrutura visual da página, o Meta Pixel, os links de checkout, as imagens incorporadas e as demais seções aprovadas.

## Alterações realizadas

- Faixa móvel e fixa no topo destacando a condição promocional ativa.
- Aviso principal da oferta ampliado, com contraste e leitura melhores no mobile.
- Aviso da seção de preços também ampliado e reforçado.
- Copy principal reescrita em linguagem mais direta e informal.
- Mensagens de venda reformuladas para explicar de forma simples como o pet personalizado pode gerar encomendas.
- Remoção da expressão formal “alto valor percebido”.
- Bloco de comparação reforçado com a lógica visual do “antes e depois”.
- Área de resultados das alunas reconstruída com quatro espaços para: foto real, valor da venda, comentário e nome.
- A área de resultados permanece oculta até o envio das provas reais.

## Sobre a urgência

A página usa uma urgência forte, mas sem inventar quantidade exata de vagas. A frase informa que a condição promocional pode sair do ar sem aviso. Um número como “restam 3 vagas” só deve ser publicado quando corresponder à disponibilidade real.

## Como ativar os resultados das alunas

No `index.html`, procure por `RESULTADOS DAS ALUNAS`. Substitua os quatro modelos com:

1. foto real do amigurumi;
2. valor real pelo qual foi vendido;
3. comentário real e espontâneo da aluna;
4. nome da aluna.

Depois, remova apenas o atributo `hidden` da seção `#resultados-alunas`.

## Elementos preservados e conferidos

- Meta Pixel: `1696881438314279`.
- Checkout Plano Essencial: `https://pay.cakto.com.br/y2mbwcs_970161`.
- Checkout Plano Completo: `https://pay.cakto.com.br/fdf3cfe`.
- Imagens incorporadas diretamente no HTML.
- Responsividade para mobile e desktop.

## Publicação

Substitua o arquivo atual pelo novo `index.html`. Não é necessário subir uma pasta de imagens.
