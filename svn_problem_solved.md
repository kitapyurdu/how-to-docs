# svn add * işlemini geri alma

<b>*svn add file_name*</b>  şeklinde kullanmamız gerekirken <b>*svn add **</b>  şeklinde yanlış bir kullanım yaptığımızda bütün dosyaları commit için ekleyecektir.


Eğer bütün dosyaları göndermek istemiyorsanız (nbproject dosyası gibi) ve bu işlemi geri almak istiyorsanız:

> *svn delete --keep-local nbproject*

yazarak bu işlemi geri alabilirsiniz.

Bu işlem yerel dosyaları koruyup sadece svn deposundan eklenen dosyaları kaldırır. Daha sonra <b>svn st</b> komutu ile tekrar dosyalarınızın son durumunu kontrol edebilirsiniz.     

Ayrıca bakınız:   
. [svn add](http://svnbook.red-bean.com/en/1.6/svn.ref.svn.c.add.html)  
. [svn delete](http://svnbook.red-bean.com/en/1.6/svn.ref.svn.c.delete.html)   
. [svn st](http://svnbook.red-bean.com/en/1.6/svn.ref.svn.c.status.html)
