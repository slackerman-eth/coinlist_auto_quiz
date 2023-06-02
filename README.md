# Coinlist Auto Quiz
## Neon

На странице с квизом жмём F12 и вставляем код в консоль

```js
let run = async () => {
    let a = document.body.querySelectorAll(".quiz")[0].querySelectorAll(".c-label--inline"),
        b = [
        "50,000,000",
        "Users in the waiting room for the sale will be given a random spot in the queue when the sale starts. Users who arrive after the sale starts for the sale will be placed behind those in the waiting room",
        "Neon is an EVM that allows Ethereum dApps to function within Solana",
        "USDC, USDT",
        "$0.10 per token, $500 max purchase amount",
        "The user's purchase may be canceled and the user may be banned from future CoinList sales",
        "CoinList.co",
        "The user's account will be terminated and all purchases will be canceled"];
    for (let c = 0; c < a.length; c++) - 1 !== b.indexOf(a[c].textContent) && (a[c].querySelectorAll(".c-input")[0].checked = !0);
    await (a => new Promise(b => setTimeout(b, a)))(200), document.getElementsByClassName("js-submit")[0].click()
};
run();
```

## Archway

```js
let run = async () => {
    let a = document.body.querySelectorAll(".quiz")[0].querySelectorAll(".c-label--inline"),
        b = [
        "30,000,000",
        "Users in the waiting room for the sale will be given a random spot in the queue when the sale starts. Users who arrive after the sale starts for the sale will be placed behind those in the waiting room",
        "Archway is a Cosmos-native Layer 1 blockchain that allows developers to capture the value created by their dApps",
        "USDC, USDT",
        "$0.20 per token, $1000 max purchase amount",
        "The user's purchase will be settled at the completed amount",
        "CoinList.co",
        "The user's purchase may be canceled and the user may be banned from future CoinList sales"];
    for (let c = 0; c < a.length; c++) - 1 !== b.indexOf(a[c].textContent) && (a[c].querySelectorAll(".c-input")[0].checked = !0);
    await (a => new Promise(b => setTimeout(b, a)))(200), document.getElementsByClassName("js-submit")[0].click()
};
run();
```
