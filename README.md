## Futtatás helyileg


### 1. Telepítsük a MongoDB-t

Innen tölthető le: https://docs.mongodb.com/manual/administration/install-community/

### 1.1 Hozzunk létre a Yeetbay adatbázisunkban 2 objectet, egy product-ot és egy user-st.
Majd a mongoDbFiles mappában található 2 JSON filet importáljuk bele, így kapunk alapból a webshophoz termékeket.

### 2. Backend futtatása

```
$ cd Backend
$ npm install
$ npm start
```
Nyissunk egy új terminált

### 3. Frontend futtatása

```
$ cd frontend
$ npm install
$ npm start
```

### 4. Admin felhasználó

- Ezt bemásolva kapunk egy belépési adat párost: http://localhost:5000/api/users/createadmin

Admin e-mail: admin@example.com

Admin jelszó: 1234

### 5. Belépés

-http://localhost:3000/signin

### 7. Termékek készítése

-http://localhost:3000/products

