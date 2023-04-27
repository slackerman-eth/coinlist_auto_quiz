# Coinlist Auto Quiz

На странице с квизом жмём F12 и вставляем код в консоль

```js
let run = async () => {
    let a = document.body.querySelectorAll(".quiz")[0].querySelectorAll(".c-label--inline"),
        b = [
        "3,000,000",
        "Users in the waiting room for the sale will be given a random spot in the queue when the sale starts. Users who arrive after the sale starts for the sale will be placed behind those in the waiting room.",
        "CyberConnect is a decentralized social network that allows users to own their digital identity, content, connections, and monetization channels",
        "USDC, USDT",
        "$1.80 per token, maximum purchase of $500",
        "The user's purchase may be canceled and the user may be banned from future CoinList sales",
        "CoinList.co",
        "The user's account will be terminated and all purchases will be canceled"];
    for (let c = 0; c < a.length; c++) - 1 !== b.indexOf(a[c].textContent) && (a[c].querySelectorAll(".c-input")[0].checked = !0);
    await (a => new Promise(b => setTimeout(b, a)))(200), document.getElementsByClassName("js-submit")[0].click()
};
run();
```
