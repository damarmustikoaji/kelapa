# kelapa
API Automation Testing using Postman Collection - Newman

## Description
Automation Testing API menggunakan collection Postman dengan Newman. Dengan file collection berupa format JSON dijalankan menggunakan perintah newman. Segala attribute (headers, body, dll..) dari endpoint sudah terdokumentasikan didalam collection, dan script test didalam page endpoint secara otomatis juga dijalankan saat running di newman.

## Steps
- Export collection Postman berupa file json
- Install Newman
- Run Newman pada file collection postman

## Note
- Collection postman yang menggunakan environment sementara belum bisa di repository ini, jadi sementara value dari variable environment tersimpan di page langsung

## Referensi
- https://www.linkedin.com/pulse/running-postman-collections-via-github-action-nirmala-jayasanka/
- https://www.npmjs.com/package/newman
