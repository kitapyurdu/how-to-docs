# svn add * işlemini geri alama

"svn add file_name"  şeklinde kullanmamız gerekirken " svn add  * "  şeklinde yanlış bir kullanım yaptığımızda bütün dosyaları commit için ekleyecektir.

Eğer bütün dosyaları göndermek istemiyorsanız (nbproject dosyası gibi) ve bu işlemi geri almak istiyorsanız :
  - svn delete --keep-local file_name yazarak bu işlemi geri alabilirsiniz.

  Daha sonra "svn st" ile tekrar dosyalarınızı kontrol edebilirsiniz.


<b>Not : </b> Bu dokuman güncellenecektir.  
