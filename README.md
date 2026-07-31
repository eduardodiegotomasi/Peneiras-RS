# Peneiras RS

Site estático simples para publicar peneiras de futebol por ano de nascimento.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta.
3. Abra **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/root`.
6. Salve e aguarde a publicação.

## Editar as categorias

Os botões estão no arquivo `index.html`.

As páginas individuais ficam na pasta `categorias`.

## Adicionar uma peneira

Abra a página da categoria correspondente e copie o bloco:

```html
<article class="tryout-card">
  ...
</article>
```

Troque os dados e o link pela fonte oficial.
