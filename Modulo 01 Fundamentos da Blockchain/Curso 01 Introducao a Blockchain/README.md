# Gerador de Carteira Bitcoin na Testnet

Este script em JavaScript gera uma carteira de Bitcoin na rede **testnet** usando `bip32`, `bip39`, e `bitcoinjs-lib`. Ele gera um endereço Bitcoin, a chave privada correspondente e a seed mnemônica usada para criar a carteira.

## Funcionalidades

- Geração de uma frase mnemônica (BIP39).
- Conversão da mnemônica para uma seed.
- Derivação de uma carteira Bitcoin usando o padrão BIP32.
- Geração de um endereço Bitcoin na rede **testnet**.
- Exibição do endereço Bitcoin, chave privada e frase mnemônica no console.

## Pré-requisitos

Você precisará ter o Node.js instalado para rodar este script. As bibliotecas necessárias são:

- `bip32`
- `bip39`
- `bitcoinjs-lib`

Para instalar as dependências, rode:

```bash
npm install bip32 bip39 bitcoinjs-lib

```

## Uso

   - Clone ou baixe este repositório.
   - Instale as dependências com npm install.
   - Execute o script: 
```bash
        node createWallet.js
```
O script vai gerar um endereço Bitcoin, uma chave privada e a frase mnemônica que serão exibidos no console.

## Exemplo de Saída
```bash
Carteira gerada
Endereço: 2N9u9dpfgzF8u7U6L1wL6yvF5LsGHFqK4Fd
Chave privada: cQVGjZj3g7LQX7ZD7opJzT4B5J3gK7mrsc9yZErfqMn3f7YYab8J
Seed: dust country inherit improve gossip easy jungle school page spray dry enact
```

 <font size="2"> Nota: Este script gera carteiras na rede testnet, que é uma rede de teste e não usa Bitcoins reais. Use a mainnet com cautela se modificar o script para produção.</font>

