## let e const
```js
//const e let são locais e só funcionam no escopo onde ele foi criado

console.log('existe y antes do bloco ?, y')

{
    let y=0
}
console.log('existe x depois do bloco?', y)
```

## var
```js
// var é global e poderá funcionar fora de um escopo de bloco
console.log('existe y antes do bloco ?, y')

{
    var x=0
}
console.log('existe x depois do bloco?', y)
```