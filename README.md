# Página de vendas — Meu AuMigu

Projeto estático preparado para publicação no GitHub Pages.

## Arquivos

- `index.html`: página de vendas completa.
- `README.md`: instruções de uso e publicação.

## Visualizar no computador

Você pode abrir o arquivo `index.html` diretamente no navegador. Para testar em um servidor local, execute dentro da pasta do projeto:

```bash
python -m http.server 8000
```

Depois, acesse `http://localhost:8000` no navegador.

## Publicar no GitHub Pages

1. Crie um novo repositório no GitHub.
2. Envie os arquivos `index.html` e `README.md` para a raiz do repositório.
3. No repositório, abra **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main`, a pasta `/ (root)` e clique em **Save**.
6. Aguarde o GitHub disponibilizar o endereço público da página.

## Atenção antes de publicar

Esta página foi preparada a partir de uma exportação do WordPress/Elementor e ainda utiliza arquivos externos hospedados em `artenoape.com`, incluindo imagens, fontes, estilos e scripts. Se esses arquivos forem removidos ou bloqueados no servidor original, partes do visual poderão deixar de carregar.

O formulário de pré-inscrição também dependia originalmente do WordPress/Elementor. Em hospedagem estática, como o GitHub Pages, ele precisa ser conectado a um serviço de formulário ou a um link próprio de WhatsApp antes de receber cadastros corretamente.

Também é recomendável revisar e substituir:

- links dos botões;
- texto, datas e horários;
- endereço do grupo de WhatsApp;
- integrações de formulário;
- pixels e códigos de rastreamento;
- imagens e materiais protegidos por direitos autorais.

## Estrutura mínima do repositório

```text
meu-aumigu-pagina-vendas/
├── index.html
└── README.md
```
