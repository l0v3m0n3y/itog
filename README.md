# itog
JavaScript library for itog.by
# main
```js
async function main(){
    const {itog} = require('./itog');
    const rates= new itog();
    let req=await rates.exchange_rates()
    console.log(req)
}
main()
```
