# Landing Page — Meu AuMigu

Landing page de vendas do curso **Meu AuMigu**, transformada a partir da antiga página de pré-inscrição.

## Arquivos do projeto

- `index.html`: página completa, responsiva e independente. Todas as imagens estão incorporadas no próprio HTML em Base64.
- `README.md`: instruções de publicação e edição.

> Este projeto não utiliza e não precisa de pasta `assets`.

## O que foi alterado

- Remoção do formulário de pré-inscrição, grupo e live de abertura.
- Nova promessa principal voltada a pets personalizados.
- Jornada de vendas completa: dor, solução, galeria, método, técnicas, público, professora, confiança, oferta, garantia e FAQ.
- Botões ligados ao checkout do Meu AuMigu.
- Galeria horizontal de peças no estilo streaming, com parte do próximo card visível no celular.
- Botão de compra fixo no rodapé da versão mobile.
- Identidade visual e paleta do Meu AuMigu preservadas.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie apenas `index.html` e `README.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/root`.
6. Salve e aguarde a publicação.

## Alterar o checkout

No final do `index.html`, localize:

```js
const CHECKOUT_URL = 'https://pay.kiwify.com.br/tD3GMZG';
```

Substitua apenas o endereço entre aspas. Todos os botões serão atualizados automaticamente.

## Provas sociais

A página usa atualmente galeria visual dos pets, números de autoridade da professora, comunidade, suporte, garantia e acesso vitalício. Não foram inventados depoimentos. Use somente prints, fotos e frases reais autorizadas.

## Observação

Como todas as imagens estão incorporadas no `index.html`, o arquivo fica maior, mas pode ser publicado sem nenhuma pasta adicional. As fontes continuam sendo carregadas pelo Google Fonts; caso falhem, a página utiliza fontes de sistema como alternativa.
