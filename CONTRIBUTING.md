# Contribuindo com a ACID

Obrigado pelo interesse em contribuir com a ACID.

A ACID é uma comunidade construída de forma colaborativa. Nosso objetivo é aprender, pesquisar e construir juntos, sempre mantendo um ambiente aberto, responsável e respeitoso.

## Como contribuir

Você pode contribuir de diversas formas:

- compartilhar conhecimento;
- corrigir ou melhorar uma documentação;
- criar pesquisas e write-ups;
- desenvolver ferramentas e projetos;
- identificar problemas;
- sugerir melhorias;
- participar de discussões;
- ajudar outros membros da comunidade.

Não é necessário ser especialista para contribuir. A ACID existe justamente para que possamos evoluir juntos.

## Fluxo de contribuição

Para alterações em repositórios da ACID, utilizamos o seguinte fluxo:

1. Crie uma branch a partir da `main`.
2. Faça suas alterações.
3. Adicione as alterações ao staging.
4. Crie um commit descrevendo o que foi feito.
5. Envie sua branch para o GitHub.
6. Abra um Pull Request.
7. Aguarde a revisão e discussão das alterações.
8. Após a aprovação, a alteração poderá ser incorporada à `main`.

Exemplo:

```bash
git switch main
git pull

git switch -c tipo/minha-alteracao

git add .
git commit -m "tipo: descrição da alteração"

git push -u origin tipo/minha-alteracao
