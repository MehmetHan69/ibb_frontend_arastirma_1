# ibb_frontend_arastirma_1
ilk ders araştırma ödevi
_________________________________________________________________________________________

 **framework ve libraries farkları nelerdir?

 Framework ve Library 'in  ortak noktası birileri tarafından yazılan ve başkaları tarafından kullanılabilen ortak kod yapıları olmasıymış
 aslında amaçlarıda ortakmış ama teknik anlamda farklılıkları varmış

 teknik anlamdaki farkı şu şekilde açıklanmış:
 ''  Library ile Framework ‘ün ayrıştığı nokta teknik kısımdır. İki arasındaki temel teknik fark,  kodun nasıl çağrıldığıdır. Library kullanırken, library size bazı özellikler vererek kullanmanızı sağlar, bu şekilde almış olduğunuzu kodu kendi sisteminize uygularken size kodu nerede ve ne zaman kullanacağınıza karışmaz veya bir diğer deyişle dikte etmez.  Framework ise Library'in tersine  kullanacağız özelliğe göre kodu nerede ve ne zaman kullanacağınız söyler, kullanacağız bu işlev, eğer Framework dokümanın belirtildiği gibi kullanılmaz ise kullanım dışı kalır.  ''


** Compiler nedir?
compiler derleyici anlamına geliyormuş peki derleyici ne anlama geliyor derleyici programcının yazdıgı kodu bilgisayarın anlayabilecegi makine diline çeviren 0 - 1 lere çeviren aracı yazılım Derleyici sayesinde geliştiriciler farklı programlama dillerini kullanarak aynı işlevi yerine getiren yazılımlar üretebilirler. Üstelik Complier’ların varlığı, çok fazla programlama dilinin olmasına ve geliştiricilerin alternatif dillerle çalışmasına yardımcı olmaktadır.



**Interpreter Nedir ?
yorumlayıcı anlamına gelmekteymiş yorumlayıcılar kodları blok blok satır satır halinde çalıştırırlar 
blokları sırası gelmeden değerlendirmezler Bu nedenle, sonraki satırdaki hatalar ve kodun bütününü etkileyen iyileştirmeler yorumlayıcılar tarafından yakalanamazlar. Kodu parçalar halinde değerlendirmek amacıyla kullanılırlar



**ASCII karakter ve unicode nedir ?

Bilgisayarların iki farklı elektrik sinyali ile çalıştığını, bu iki farklı sinyalin de 0 ve 1 sayıları ile temsil edildiğini,
bilgisayarla metin işlemleri yapabilmek için ise bu sayıların belli karakterlerle eşleştirilmesi gerekiyo 
0 devrede elektrik olmadıgını 1 ise var oldugu anlamına geliyormuş ''ASCII adı verilen sistem, birtakım sayıların birtakım karakterlerle eşleştirildiği basit bir tablodan ibarettir ''
unicode her bir karakter ve sembolleri benzersiz bir rakam yardımıyla oluşturmak için geliştirilen bir metin standartıdır.
ASCII nin daha geliştirilmiş versiyonu diyebiliriz ''ASCII karakterler sadece İngilizce üzerinde etkili olurken, Unicode tamamen evrenseldir.'' , '' Unicode’un farklı sürümleri sayesinde İbranice ve Arapça gibi kompleks diller başta olmak üzere Çince gibi karmaşık diller kolayca dijital ortamlara aktarılabilmektedir ''


**Semantic non semantic nedir?
''  Semantic (anlamsa) ve non-semantic (anlamsal olmayan) terimleri aslında HTML’deki tagler için kullanılır.
Semantic, kodun yapısını ve anlamını açık bir şekilde ifade etmeyi ifade eder. Kodun okunabilirliğini ve aslında arama motorlarında o elementi anlamlandırmayı sağlar. İçeriğin ne olduğu hakkında bilgi verir. Örnek olarak <header>, <footer> verilebilir.
Non-semantic, kodun yapısını ve anlamını anlatmaktan ziyade biçimlendirme odaklıdır. Buna örnek olarak <div> elementi verilebilir. <div> elementinin herhangi bir özel anlamı yoktur. Ancak bir websitesini şekillendirmede sıkça kullanılan bir elementtir. ''




**Get-Post nedir?
 Get Formdan gönderilen veri gideceği hedefe ilerlerken aynı zamanda url kısmında da bu giden verinin görünmesini sağlar,
 Post metodunda formlara girilen bilgiler gönderilirken görünmemektedir. Bundan dolayı daha güvenlir. Ayrıca büyük miktardaki veriler de bu yöntemle gönderilmektedir.



**Ajax nedir ?

Sunucuya gelen herhangi bir isteği arkaplanda işleyerek web uygulamalarının eşzamanlı olmadan çalışmasına olanak sağlayan bir takım web geliştirme teknikleridir
aslında işlem yapılırken sitenin yenilenmeden Asenkron şekilde bagımsız çalışmasını saglıyor genelde puanlama sistemlerinde sohbet odalarında gibi örneklersek daha iyi aklımızda kalır 


**CDN nedir?

 yoğun veri kullanan uygulamalar için web sayfası yüklenmesini hızlandıran bir birbirine bağlı sunucular ağıdır 
 ''Bir kullanıcı bir internet sitesini ziyaret ettiğinde o internet sitesinin sunucusundaki verinin kullanıcının bilgisayarına ulaşmak için internet boyunca yolculuk etmesi gerekmektedir. Kullanıcı o sunucudan uzakta bulunuyorsa video veya internet sitesi görüntüsü gibi büyük bir dosyayı yüklemek uzun zaman alacaktır. Bunun yerine web sitesi içeriği, kullanıcılara coğrafi olarak yakın CDN sunucularında depolanır ve bilgisayarlarına çok daha hızlı ulaşır.''


**crossorgin nedir
 Kaynaklar arası varlık paylaşımı (CORS), uygulamaları entegre etmeye yarayan bir mekanizmadır. CORS, bir etki alanına yüklenen istemci web uygulamalarının farklı bir etki alanındaki varlıklarla etkileşime girmesi için bir yol tanımlar. Karmaşık uygulamalar genellikle istemci tarafı kodlarında üçüncü taraf API'lere ve varlıklara başvurduğundan, bu yol kullanışlıdır.
