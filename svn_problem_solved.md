# svn add * işlemini geri alama

<b>svn add file_name</b>  şeklinde kullanmamız gerekirken <b> svn add  * </b>  şeklinde yanlış bir kullanım yaptığımızda bütün dosyaları commit için ekleyecektir.

Eğer bütün dosyaları göndermek istemiyorsanız (nbproject dosyası gibi) ve bu işlemi geri almak istiyorsanız :

> <i>svn delete --keep-local path</i>  

yazarak bu işlemi geri alabilirsiniz. Daha sonra <b>svn st</b> ile tekrar dosyalarınızı kontrol edebilirsiniz.


<b>Not : </b> Bu doküman güncellenecektir.
