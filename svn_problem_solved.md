# svn add * işlemini geri alama

<b>svn add file_name</b>  şeklinde kullanmamız gerekirken <b> svn add  * </b>  şeklinde yanlış bir kullanım yaptığımızda bütün dosyaları commit için ekleyecektir.

Eğer bütün dosyaları göndermek istemiyorsanız (nbproject dosyası gibi) ve bu işlemi geri almak istiyorsanız :

> <i>svn delete --keep-local path</i>  

yazarak bu işlemi geri alabilirsiniz.

Bu işlem yerel dosyaları koruyup sadece svn deposundan eklenen dosyaları kaldırır.

Daha sonra <b>svn st</b> ile tekrar dosyalarınızı kontrol edebilirsiniz.


<b>Not : </b> Bu doküman güncellenecektir.
