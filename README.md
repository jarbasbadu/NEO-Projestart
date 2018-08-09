

## Instruções para instalação do projeto

Clone esse repositório e instale suas dependências:

```bash
git clone https://github.com/jetebusiness/NEO-Projestart.git
cd NEO-Projestart
npm install
```

## Iniciando o Desenvolvimento

Dentro da pasta onde o *packages.json* encontra-se, execute o comando
```bash
npm run watch
```
Para iniciar o watcher/compiler dos resources.
Enquanto ele estiver ativo, toda vez que você salvar algum arquivo .js ou .scss dentro da pasta /resources ele automaticamente irá re-compilar o código.

## Compilando para produção

Dentro da pasta onde o *packages.json* encontra-se, execute o comando
```bash
npm run prod
```
Seu código dentro da pasta resources irá ser compilado para produção com minificação e uglifyJS.
