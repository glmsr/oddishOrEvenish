# oddishOrEvenish

Bir sayının Tek mi Çift mi olduğunu belirleyen bir işlev oluşturun. Bir sayı, tüm basamaklarının toplamı tek ise tek, tüm basamaklarının toplamı çift ise bir sayıdır. Bir sayı tek ise, "Odd" döndürün. Aksi takdirde, "Even" değerini döndürün. 

```
function oddishOrEvenish(num){
    let str = num.toString().split('')
    let result = 0;
  for(let i = 0; i < str.length; i++){
    result += Number(str[i])
  }
    if(result % 2 === 0){
    console.log('Even')
   }else{
    console.log('Odd')
  }
}
```
