<h1> Git Nedir? </h1>
<p>
Git, yazılım geliştirme sürecinde kullanılan bir dağıtık versiyon kontrol sistemidir. Bu sistem, geliştirme sürecinde yapılan değişikliklerin takibini yapar ve kaynak kodu, belgeleme, konfigürasyon dosyaları gibi projenin tüm dosyalarını yönetir. Git, bir projenin birden fazla kişi tarafından geliştirildiği durumlarda işbirliği yapmayı kolaylaştırır. Her kullanıcının kendi yerel bir kopyası olduğu için, herkes aynı anda çalışabilir ve değişiklikler bir merkezi sunucuda değil, kullanıcıların kendi kopyalarında saklanır ve birbirleriyle senkronize edilir.

Git, açık kaynaklı ve ücretsiz bir yazılımdır. Git, Linux çekirdek geliştiricisi Linus Torvalds tarafından 2005 yılında geliştirilmiştir. Torvalds, diğer versiyon kontrol sistemlerinin yetersiz kaldığını düşünerek Git'i oluşturdu. Git, özellikle açık kaynak yazılım projelerinde yaygın olarak kullanılır, ancak birçok büyük şirket tarafından da kullanılmaktadır.

Git, merkezi bir kontrol sistemine karşı dağıtık bir sistemdir. Merkezi kontrol sistemlerinde, tüm dosyalar merkezi bir sunucuda saklanır ve kullanıcılar sunucudan dosyaları indirip değişikliklerini yaparlar. Bu sistemde, sunucu arızalanırsa veya erişilemez hale gelirse, dosyalara erişmek mümkün olmaz. Ancak Git'te her kullanıcının kendi yerel bir kopyası vardır, bu nedenle sunucuda bir arıza olsa bile kullanıcılar kendi kopyaları üzerinde çalışmaya devam edebilirler.

Git'in birçok avantajı vardır. İşbirliği yapmayı kolaylaştırır ve projenin tarihçesini takip etmenizi sağlar. Her değişiklik kaydedildiği için bir hatanın nerede yapıldığını kolayca bulabilirsiniz. Ayrıca, birden fazla dalda çalışmayı da kolaylaştırır. Bir dal, projenin ana kodundan ayrılmış bir kopyasıdır ve farklı özellikler veya değişiklikler için kullanılabilir. Bu şekilde, bir değişiklik bir dalda test edilebilir ve daha sonra ana koduna entegre edilebilir.

Git, komut satırı arayüzü ile kullanılabilir. Ancak, birçok grafik arayüzü de mevcuttur, bu nedenle komut satırı kullanmak istemeyenler için de uygun bir arayüzü vardır. Git, herhangi bir işletim sistemi üzerinde çalışabilir ve tüm büyük programlama dilleriyle uyumludur.
</p>
<br>
<br>
<h1> Git Neden Kullanılmalıdır? </h1>
<p>
Git modern yazılım geliştirme sürecinde çok önemli bir araçtır. Yazılımcıların kullandığı en popüler versiyon kontrol sistemlerinden biridir. Git açık kaynaklı bir yazılım olup ücretsiz olarak kullanılabilir. Git'in kullanımının yaygınlaşmasının temel nedenleri arasında, bir proje üzerinde çalışan birden fazla kişinin kolayca işbirliği yapabilmesine olanak tanıması, değişikliklerin takibini kolaylaştırması ve bir hatayı bulup düzeltmeyi basitleştirmesi yer almaktadır.

Git, yazılımcıların projeleri yönetmelerini ve takip etmelerini kolaylaştırmak için tasarlanmış bir versiyon kontrol sistemidir. Projenin tamamının bir kopyasını barındıran bir depoyu yönetir. Bu depo tüm kod dosyalarını, yapılandırma dosyalarını ve diğer kaynak dosyalarını içerir. Bu depodaki tüm dosyalar, proje geliştirme sürecinde yapılan değişikliklerin takibi için kullanılır.

Git'in en önemli özelliklerinden biri birden fazla kişinin aynı kod tabanı üzerinde çalışabilmesini kolaylaştırmasıdır. Birden fazla kişi aynı kod tabanı üzerinde çalıştığında, Git, değişiklikleri takip eder ve değişikliklerin birbirleriyle uyumlu olmasını sağlar. Bu, projenin geliştirilmesinde işbirliği yapmayı kolaylaştırır ve ekip üyelerinin aynı kod tabanı üzerinde çalışmasını sağlar.

Git, her yapılan değişikliği takip eder ve tüm değişikliklerin bir tarihçesini tutar. Bu, bir hatanın nerede yapıldığını bulmayı kolaylaştırır ve geri alma işlemi gibi birçok işlemi basitleştirir. Git farklı sürümler arasında geçiş yapmayı da kolaylaştırır. Bu, bir projenin eski bir sürümüne geri dönmeyi veya bir önceki sürümdeki bir hata düzeltmesini kullanmayı kolaylaştırır.

Git bir dalda çalışmayı kolaylaştırır. Bir dal, projenin ana kodundan ayrılmış bir kopyasıdır ve farklı özellikler veya değişiklikler için kullanılabilir. Bu, bir değişikliği test etmek için bir dalda kullanmayı ve daha sonra ana koduna entegre etmeyi kolaylaştırır.

Sonuç olarak, Git, yazılım geliştirme sürecinde çok önemli bir araçtır ve birçok yazılımcı tarafından kullanılır. Git, projelerin yönetimini kolaylaştırır, değişikliklerin takibini kolaylaştırır ve işbirliği yapmayı basitleştirir
<p>
<br>
<br>
<h1> Sık Kullanılan Git Terimleri</h1>

## Git Config
<p>
 Git yapılandırma ayarlarını yapılandırmak için kullanılır. Bu komut ile kullanıcı adı, e-posta adresi, editör seçimi, renkler gibi birçok ayar yapılabilir. Bu ayarlar, global olarak (tüm Git projeleri için) veya yerel olarak (yalnızca bir projede) yapılabilir.

 Örneğin, git config --global user.name "Buse" komutu ile Git kullanıcı adı "Buse" olarak ayarlanabilir. git config --local core.editor vim komutu ile de, mevcut Git projesinde kullanılacak editör VIM olarak ayarlanabilir.
                
 Bu komut ayrıca --list seçeneği kullanılarak yapılandırma ayarlarının bir listesini de görüntüleyebilirsiniz.
</p>
<br>



## Git Init
<p>
Bir dizinde yeni bir Git deposu oluşturur. Bu komutu kullandığınızda, dizinin içinde bir .git klasörü oluşturulur ve bu klasör Git deposunun kalbidir. Bu klasör içinde depo ayarları, tarihçesi ve diğer tüm Git verileri saklanır. git init komutu, mevcut bir projeye Git özellikleri eklemek veya tamamen yeni bir proje oluşturmak için kullanılabilir.
</p>
<br>

## Git Checkout
<p>
Git Checkout, Git'in önemli bir komutudur ve çeşitli amaçlarla kullanılabilir. En temel kullanımı, mevcut bir branch'ten başka bir branch'e geçmek için kullanılır. Bu işlemi yaparken, Git mevcut branch'in dosyalarını temizler ve seçilen branch'in dosyalarını yükler. Ayrıca, Git Checkout, commit tarihlerini geri almak, değiştirilmiş dosyaları geri yüklemek veya önceki bir versiyona geçmek için de kullanılabilir. Bu işlemler sırasında, mevcut değişikliklerin kaybolabileceği unutulmamalıdır. Git Checkout ayrıca, farklı bir branch'teki dosyaları geçici olarak görüntülemek veya farklı bir commit'ten dosyaları geri yüklemek için de kullanılabilir.
</p>
<br>

## Git Branch
<p>
Git branch, bir Git deposunda birden fazla geliştirme yolu veya sürümün yönetilmesini sağlayan bir Git özelliğidir. Her bir branch, depodaki farklı bir dizi değişiklikle birleştirilir. Bu, farklı geliştirme ekiplerinin veya farklı sürümlerin aynı kod tabanında yönetilmesine olanak tanır. Yeni bir branch oluşturmak, mevcut kod tabanının bir kopyasını alır ve üzerinde yeni değişiklikler yapılmasına olanak tanır. Bu, birden çok özellik veya sürüm üzerinde çalışmanın daha organize ve güvenli hale getirilmesine yardımcı olur.
</p>
<br>

## Git Merge
<p>
Git Merge, iki farklı Git branch'ini birleştirmek için kullanılan bir Git komutudur. Merge işlemi ile, farklı branch'lerde yapılmış olan değişiklikler tek bir branch'te birleştirilerek projenin bütünlüğü korunur. Git Merge, projelerdeki farklı versiyonların birleştirilmesi, farklı özelliklerin bir araya getirilmesi veya farklı geliştirici ekiplerinin çalışmalarının birleştirilmesi gibi durumlarda kullanılır. Merge işlemi sonrasında, projenin tarihçesi ve değişiklik geçmişi değişebilir ve farklılık gösterebilir.
</p>
<br>

## Git Commit
<p>
Git commit, Git'in temel özelliklerinden biridir ve dosya değişikliklerinin yerel bir depoya kaydedilmesini sağlar. Bu, projenin herhangi bir noktasında geri dönülmesi gerektiğinde veya bir hata oluştuğunda değişikliklerin kaydedilmesini ve geri alınmasını kolaylaştırır. Git commit, bir veya birden fazla dosya için bir açıklama ile birlikte yapılır. Bu açıklama, yapılan değişiklikleri açıklayan bir mesajdır ve projenin geçmişindeki belirli bir noktanın açıklamasını sağlar.
</p>
<br>

## Git Add
<p>
Git Add, Git'in dosya takip sisteminde bir dosyanın değişikliklerini veya yeni bir dosyayı takip etmesini sağlayan bir komuttur. Bu komut, değişikliklerin kaydedilmesi için bir sonraki adım olan Git Commit işlemi için hazırlık yapar. Git Add komutu, değişiklikleri veya yeni dosyaları Git deposunun "stage" adı verilen bir bölümüne ekler, böylece Git Commit komutuyla bu değişiklikler veya dosyalar depoya kaydedilebilir.
</p>
<br>

## Git Push
<p>
Yerel bir Git deposundaki değişiklikleri uzak bir Git deposuna yüklemek için kullanılır. Bu işlem, yerel deponuzdaki değişikliklerin bir kopyasını uzak bir depoya gönderir ve böylece işbirliği yaptığınız diğer kişilerin bu değişiklikleri görmelerini sağlar. git push komutu ayrıca uzak depodaki değişikliklerin yerel depoya indirilmesine de yardımcı olabilir. Komutun kullanımı git push *uzak* *branch* şeklindedir, burada *uzak* uzak depo adı, *branch* ise yüklemek istediğiniz yerel dal adıdır.
</p>
<br>

## Git Pull
<p>
bir Git deposundan uzak bir depoya değişiklikleri çekmek için kullanılır. Bu komut, değişiklikleri almak için önce git fetch komutunu çağırır ve ardından yerel kopyanın mevcut durumuna göre depodaki değişiklikleri birleştirmek için git merge komutunu kullanır. Yani git pull, depodaki en son değişiklikleri yerel depoya getirir ve yerel deponuzdaki dosyaları günceller.
</p>
<br>

## Git Diff
<p>
Git Diff, değişikliklerinizi takip etmenize ve karşılaştırmanıza yardımcı olan bir Git komutudur. Bu komut, değişikliklerinizi gösterirken, hangi satırların eklenip/hangi satırların silindiğini belirginleştirir. Ayrıca, değişikliklerin yapıldığı dosyaları ve satırları da gösterir. Bu sayede, yapılan değişikliklerin detaylı bir şekilde incelenmesine olanak sağlar.
</p>
<br>

## Git Stash
<p>
Git Stash, çalışma dizininizdeki ancak henüz tamamlanmayan değişiklikleri geçici olarak saklamak için kullanılan bir Git komutudur. Özellikle birden fazla dalda çalışırken ve hızlıca başka bir işe geçmeniz gerektiğinde faydalıdır. Bu sayede, yarım kalan değişiklikleriniz başka bir yerde saklanır ve daha sonra çalışmanıza geri döndüğünüzde yeniden uygulayabilirsiniz. Bu, çalışma dizininizde yarım kalan değişikliklerinizi kaydetmenizi ve henüz hazır olmadığınız değişiklikler üzerinde çalışırken başka bir işe geçmenizi sağlar.
</p>
<br>

## Git Log
<p>
Git Log, Git version kontrol sistemine kaydedilen commit geçmişini görüntülemek için kullanılan bir komuttur. Bu komut, bir projenin tüm commit geçmişini, kimin hangi değişiklikleri yaptığını, ne zaman yaptığını, hangi dosyaların değiştirildiğini ve değişikliklerin özeti gibi birçok bilgiyi gösterir. Ayrıca, Git Log komutu, bir projenin commit geçmişini filtrelemek, sıralamak ve belirli değişiklikleri takip etmek için de kullanılabilir.
</p>
<br>

## Git Fetch
<p>
Git fetch, uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel deponuza indiren bir komuttur. Bu komut, yerel deponuzun mevcut çalışma durumunu güncellemeden uzaktaki verileri indirir, çalışmanızı olduğu gibi bırakır ve getirilen içerik gitcheckout komutu kullanılarak açıkça kontrol edilir.
</p>
<br>

## Git RM
<p>
Git deposundan bir dosya veya dizin silmek için kullanılır. Bu komut, sadece dosyaları git deposundan siler, ancak yerel dosyaları silmez. Eğer bir dosyayı yerel depodan da silmek isterseniz, ayrıca rm komutunu kullanmanız gerekebilir. git rm komutu, silinmiş dosyaları bir sonraki commit için hazırlar ve git deposundaki tarihçeden de silinir.
</p>
<br>

## Git Reset
<p>
Git Reset, bir önceki commit'e geri dönmek için kullanılan bir Git komutudur. Bu komut, bir dosyanın veya bir dizi dosyanın içeriğini geri alabilir veya tüm commit geçmişini silerek projenin bir önceki durumuna geri dönebilir. Git Reset, kullanıcılara, hatalı veya gereksiz değişiklikleri geri almak veya bir proje dosyasının önceki bir sürümüne geri dönmek gibi farklı senaryolarda yardımcı olabilir. Ancak, bu komutun dikkatli kullanılması gerektiği ve geri alınan herhangi bir değişikliğin geri getirilemeyeceği unutulmamalıdır.
</p>
<br>
<br>

## Author
<hr>

[Buse Nur Çetin](https://github.com/busenurcetin)
