## ResyDb - Json Tabanlı Gelişmiş Modül! 

# Setup

```js
const Database = require("resydb");
const db = new Database("./all.json")
```

# Tanımlama;

```js
db.on("connect",{ 
content: "VeriTabanı Aktifleştirildi! "
})

- Veriyi Eklemek:
db.set("value", "value");

- Veriyi Aktarmak:
db.get("value");

- Veriyi Silme:
db.delete("value");

-Veriyi Kontrol Etmek:
db.fetch("value");

- Veriye Miktar Ekleme:
db.add("value", 1); 

- Veriyi Silme:
db.delete("value");

