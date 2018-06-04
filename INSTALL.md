## Instalação do npm

Antes de tudo, vamos precisar instalar o *Node.js* e seus gerenciador de pacotes, `npm`.
Para tal vamos fazer uso de um gerenciador de versões chammado [`nvm`](https://github.com/creationix/nvm).

Abra a linha de comando (Terminal no Ubuntu ou <kbd>Ctrl</kbd> + <kbd>alt</kbd> + <kbd>t</kbd>) e execute o seguinte comando:

```sh
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
```

Feito isso, vamos fechar e reabrir a linha de comando. Execute o seguinte comando:

```sh
nvm --version
```

Se não acontecer nenhum erro, a instalação foi um sucesso.

Para terminar a instalação, vamos ver se temos o Node.js instalado:

```sh
node --version
```

Se não houver Node.js instalado ou a versão instalada for inferior ao 9.0.0, vamos instalar a mais nova:

```sh
nvm install 9
nvm use 9
```

A primeira linha é responsável por instalar a versão 9 do Node.js. 
A segunda indica que você deseja usar a versão 9.

Para terminar, vamos verificar se o `npm` foi instalado:

```sh
npm --version
```
