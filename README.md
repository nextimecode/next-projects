<p align="center">
  <a href="https://github.com/chakra-ui/chakra-ui">
    <img src="./images/logo_text.png" alt="Chakra logo" />
  </a>
</p>

<h1 align="center">Seja bem-vindo à NeXTIME 🦅</h1>

Aqui está a documentação do fluxo de desenvolvimento Web com NextJS

## Primeiro precisamos entender algumas coisas:

Os nossos 

Primeiro, rode o servidor de desenvolvimento:

```bash
yarn dev
```

Abra [http://localhost:3000](http://localhost:3000) com o seu navegador para ver o resultado.

## :books: Aprenda Mais ##

Para aprender mais sobre Next.js, de uma olhada nas seguintes fontes:

- [Documentação Next.js](https://nextjs.org/docs) - Aprenda sobre características e API's de Next.js.
- [Aprenda Next.js](https://nextjs.org/learn) - um tutorial interativo de Next.js.

Você pode verificar o [repositório no GitHub do Next.js](https://github.com/vercel/next.js/) - comentários e contribuições serão bem vindas!

## Deploy na Vercel

A forma mais simples de fazer o deploy de Next.js é utilizando a [Plataforma Vercel](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) dos mesmos criadores do Next.js.

Verifique nossa [documentação de deploy do Next.js](https://nextjs.org/docs/deployment) para mais detalhes.

## *Checklist para subir o código*

1. Ir à main, pois é preciso verficar se há código novo e baixá-lo para deixar tudo compátivel.
```
$git checkout main
$git pull
```
2. Voltar à feature que estava trabalhando
```
$git checkout nome_da_feature
```
3. Mesclar o código da main com a sua feature. Caso haja problemas, devem ser reparados.
```
$git merge main
```
4. Agora a feature esta pronta para subir, então é necessário abrir uma release respeitando o controle de versionamento.
```
$git checkout -b release/x.y.z
```
5. Atualizar no package.json para a versão da release.
```
"version": "x.y.z"
```
6. Fazer um commit para subir essa alteração
```
$git add .
$git commit -m "citar alteração realizada"
```
7. Enviar essa branch
```
$git push --set-upstream origin release/x.y.z
```
8. Para fazer o Pull Request, deve-se entrar no site do github e clicar em: compare && pull request
9. Selecionar os revisores (reviewers), os participantes das alterações (assigners), os tipos de alterações (labels) e o projeto alterado.
10. Caso as alterações sejam aceitas, editar a tag da branch main para ficar de acordo com a release. A tag agora deve ser **x.y.z**.

>

Desenvolvido por [NeXTIME Tecnologia](https://github.com/nextimecode)
