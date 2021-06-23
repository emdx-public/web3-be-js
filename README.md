
## Challenge interpretación solidity

Este challenge tiene como objetivo usar herramientas básicas como js y git para conecterse, leer, interpretar y procesar información de transacciones que interactuan con contratos escritos en solidity.


Para esto se pide que el candidato realice las siguientes tareas:

1. Cree un repositorio público de Bitbucket/Github en su cuenta para el challenge, usando una rama para desarrollo: 'development'
2. Inicialice el repositorio para nodejs, ignorando node_modules, logs, etc.
3. Instalar las librerias necesarias para poder interactuar con blockchains EVM y procesar información de contratos.
4. Instanciar web3 o etherjs con un RPC público (en este caso se pide Polygon)
5. Teniendo como punto de partida esta transaccion [0x2b1cb0ee5c14b33d1871a671c235dce2972861a1ad1410659251f0b9d7fac39f](https://polygonscan.com/tx/0x2b1cb0ee5c14b33d1871a671c235dce2972861a1ad1410659251f0b9d7fac39f) y usando el RPC instanciado previamente, se pide:

a) Usar los métodos correspondientes de web3 o etherjs para obtener información programática en JSON de la transacción.

b) Obtener el ABI y bytecode del contrato con el que se interactua y guardarlos en los archivos correspondientes.

c) Interpretar el event log, para mostrar por consola (teniendo el abi correspondiente) los eventos decodeados e interpretar la información de cada uno de los logs.


6. Crear un archivo index.js que al ejecutarlo con el interpreté de nodejs devuelva los eventos interpretados de dicha transacción para poder ser fácilmente leidos.

7. Al terminar, mergear rama de development a main o master y enviar url del repositorio.


Referencias:

[Event logs](https://medium.com/mycrypto/understanding-event-logs-on-the-ethereum-blockchain-f4ae7ba50378)

[Web3 doc](https://web3js.readthedocs.io/en/1.0/web3-eth.html)

[topics & getPastLogs](https://ethereum.stackexchange.com/questions/61585/how-to-setup-topics-for-function-getpastlogs)
