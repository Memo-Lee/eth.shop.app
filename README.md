﻿# eth.shop.app

Nodemon : Oto sunucu run. Geliştirilirken kullanıldığı için devDependencies kısmın da yer alıyor. ^ işareti ise daha sonradan sürümü yükseltilebileceği için koyuluyor. Bu sebeple , install ederken ona göre edilir. Package.json kısmında oto başlatılması için script eklenir. ["start": "nodemon app.js"] eklenir ve npm start ile başlatılır. Uygulamayı nodemon başlatır.

Express : package.json kısmın da dependencies kısmın da bulunuyor çünkü sadece dev kısmın da değil projenin ayağa kalkması için de lazım.

Prettier : extencion olduğu için ^ kısmı bulunmuyor.

Middleware : Node.js uygulaması temelinde bir request ve response döngüsüdür. Biz bir istekte bulunuyoruz ve buna karşılık bir cevap istiyoruz. İşte bu request - response döngüsünün içerisindeki görevi olan her fonksiyona middleware denir. 

Template engine : Bize bu değişen içeriğin html kodu içerisinde dosya uzantısı değiştirilerek kullanmamızı sağlar. Template engineler sayesinde bir static dosyaları ve değieşn dinamik içeriği birlikte kullanabiliriz.

Mongoose : Bir nesne veri modelleme (ODM) kütüphanesi olarak mongoose, Schema yapısı sayesinde türetilen nesneleri mongoDB içerisindeki dökümanlara dönüştürür. 

https://pcatapp.onrender.com/
