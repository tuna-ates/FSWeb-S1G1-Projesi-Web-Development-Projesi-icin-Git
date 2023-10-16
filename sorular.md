# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

    Cevap:Her geliştiricinin yaptığı geliştirme veya değişikliği sürümler halinde tutan genel tabirle açık kaynak kodlu sürüm kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

    Cevap:Biri versiyon kontrol sistemi diğeri ise projelerin depolandığı erişim ağı.

3. Neden bir branch oluşturuyoruz?

   Cevap:Çalışır bir projenin üstünde proje halen çalışır konumda iken geliştirme yapmamızı sağlar.

4. Pull Request'in amacı nedir?

   Cevap:Projede yapmış olduğumuz değişiklikleri asıl proje sahibine istek atarak yapılan değişikleri onaylayarak kaydetme amacı vardır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Cevap: Komut adı:checkout   "git checkout main" kodunu kullanırım.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Cevap:
"fetch":githup daki projeleri locale çekmemizi sağlar yalnız geliştirme yaptığımız kısma
dail etmez.

"merge":birleştirme mantığı vardır fetch ettiğimiz projeyi geliştme ortamına dahil eder.

"pull" geliştirme ortamına localden direk dahil eder.

7. Merge conflict nedir?
  Cevap: İki geliştirmeci aynı projede aynı satırı aynı şekilde değişitirp çakışma yaşanması olayıdır.

8. Merge conflict'i nasıl çözeriz?

   Cevap: Çakışan kısımları düzeltip tekarar add ve commit işlemlerini gerçekleştirerek.
