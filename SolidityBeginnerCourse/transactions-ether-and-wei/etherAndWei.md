*Ether* (ETH) es una criptomoneda. *Ether* es también usada para pagar honorarios por usar la red de ethereum, como haciendo transacciones en forma de envío de *Ether*  a una dirección o interactuando con una aplicación de Ethereum. 

### Unidades de Ether 
Para especificar una unidad de *Ether*, podemos añadir los sufijos  `wei`, `gwei`, o `ether` a un número literal. 

#### `wei`
*Wei* es la subunidad más pequeña de *Ether*, nombrada en honor al criptógrafo [Wei Dai](https://en.wikipedia.org/wiki/Wei_Dai). Los números *Ether* sin un sufijo son tratados como `wei` (línea 7).

#### `gwei`
Un `gwei` (giga-wei) es igual a 1,000,000,000 (10^9) `wei`.

#### `ether`
Un `ether` es igual a 1,000,000,000,000,000,000 (10^18) `wei` (línea 11).

<a href="https://www.youtube.com/watch?v=ybPQsjssyNw" target="_blank">Mire un video con tutoriales sobre Ether y Wei</a>.

## ⭐️Misión
1. Crear una `uint` pública (`public`) llamada `oneGWei` y ponla a un `gwei`.
2. Crear una `uint` pública (`public`) llamada `isOneGWei` y ponla como el resultado de una operación de comparación entre 1 gwei y 10^9.

Consejo: Mire como esto está escrito para  `gwei` y `ether`  en el contrato.
