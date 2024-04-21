# API SPECS

## Register
### Member

```jsonc
Endpoint : '/registermember'
```

```jsonc
{
    'nama' : "Adam Levine"
    'id' : "adamlevine"
    'email' : "adamlevine@mail.com"
    'alamat' : "Neraka Jahanam"
    'no_hp' : "08816284582'
    'password' : 'maroon5'
}
```
### Kasir

```jsonc
Endpoint : '/registerkasir'
```
```jsonc
{
    'nama' : "Stefani"
    'id' : "kasirneraka"
    'email' : "adamlevine@mail.com"
    'alamat' : "Neraka Jahanam"
    'no_hp' : "08816284582'
    'password' : 'maroon5'
```

## Login

### Member
```jsonc
Endpoint : '/loginmember'
```

```jsonc
{
    'nama' : 'adam'
    'password' : 'adamlevine'
```

### Kasir
```jsonc
Endpoint : '/loginkasir'
```

```jsonc
{
    'nama' : 'kasirneraka'
    'password' : 'adamlevine'
```

## Dashboard 

### Kasir

```jsonc
Endpoint : '/admin'
```

```jsonc
{
    'id' : "kasirneraka"
    'nama' : "Stefani"
    'stock' : {
        'id_barang' : "1123"
        'nama_barang' : "SLOT"
        'deskripsi' : "Barang Slot"
        'stock' : "50"
        }
    'transaksi' : {
        'id_transaksi' : "15884"
        'user_kasir' : "Stefani"
        'user_beli' : "Adamantium"
        'waktu_beli' : "1713688121"
        'jumlah beli' : "15"
        }
}
```

### Member

```jsonc
Endpoint : '/member'
```

```jsonc
{
    'id' : "adam"
    'nama' : "Adam Levine"
    'transaksi' : {
        'id_transaksi' : "1121"
        'user_beli' : "adam"
        'nama_barang' : "SLOT"
        'jumlah' : "10"
```