# 変数とデータ型

データ型には数値型、文字列型、ブール型があります。  
取得するにはtypeof演算子を使用します。

## 数値型

数値型はnumber型とも呼ばれます。  
num01に整数ををnum2に小数を代入して表示させてみましょう。  

```js
var num01 = 12345;
var num02 = 1.2345;

console.log(typeof(num01));
console.log(typeof(num02));
```

以下の結果になるはずです。

```txt
number
number
```

## 文字列型

文字列型はstring型とも呼ばれます。  
コードを書いて表示してみましょう。

```js
var string_a = "Hello"

console.log(typeof(string_a))
```

以下の結果になるはずです。

```txt
string
```

## ブール

ブールは真偽型やboolean型とも呼ばれます。  
コードを書いて表示してみましょう。  

```js
var num_a = 1
var num_b = 10

var bool01;
bool01 = (num_a < num_b)

console.log(typeof(bool01))
```

以下の結果になるはずです。

```txt
boolean
```

[前のセクション(変数)に戻る](./02-variant.md)  
[次のセクション(配列)に進む](./04-array.md)