# Quick Checksum
English
-------------------------------------------
A Small Software to Check File Authenticity
Although I prepared this software to practice on certain Powershell commands, I decided to put it here as it is a very practical use. You can quickly determine whether two files are identical or you can check the file accuracy with a hash code you have.

It is very simple to use; 
- In the first tab in the window that opens, you enter the path to the main file you have, and as a result it lists the hashes of the main file made with different hash methods.
- If you have a hash code you want to compare, all you have to do is to compare it by pasting the hash code in the right place on the second tab. The result of the comparison automatically determines whether the hash codes are the same or not.
- If you have another file that you can physically compare, just add it to the third tab. As a result, the software automatically compares the hash codes of the two files and tells you if they are the same or not.
- If you want to copy any of the extracted hash codes, all you have to do is click on it.

The software uses the Powershell environment, I converted the software in the Source Code to executable due to Powershell's authorization error on some computers. Those who do not receive authorization errors can use Sorce Code directly if they wish but I wouldn't recommend it for practicality.
Since this software is prepared to practice many Powershell methods, it is also a document that can be examined by those who want to learn the methods. Do not hesitate to ask if there are parts that do not understand how it works.

Türkçe
-------------------------------------------
Dosya Doğruluğunu Kontrol Etmek için Ufak Bir Kod
Bu yazılımı belirli Powershell komutları üzerinde pratik yapmak için hazırlamama rağmen, çok pratik bir kullanım olduğu için buraya koymaya karar verdim. İki dosyanın aynı olup olmadığını hızlı bir şekilde belirleyebilir veya sahip olduğunuz bir Hash kodu ile dosya doğruluğunu kontrol edebilirsiniz.

Kullanımı çok kolay;
- Açılan pencerede ilk sekmede, sahip olduğunuz ana dosyanın yolunu girersiniz ve bunun sonucunda size, ana dosyanın farklı hash yöntemleriyle yapılan hash'lerini listeler.
- Karşılaştırmak istediğiniz bir Hash kodu varsa, tek yapmanız gereken Hash kodunu ikinci sekmede doğru yere yapıştırarak karşılaştırmaktır. Karşılaştırmanın sonucunda, Hash kodlarının aynı olup olmadığını otomatik olarak belirler.
- Fiziksel olarak karşılaştırabileceğiniz başka bir dosyanız varsa, onu üçüncü sekmeye eklemeniz yeterlidir. Sonuç olarak, yazılım otomatik olarak iki dosyanın Hash kodlarını karşılaştırır ve size aynı olup olmadıklarını söyler.
- Çıkarılan hash kodlarından herhangi birini kopyalamak isterseniz, tek yapmanız gereken üzerine tıklamaktır.

Yazılım Powershell ortamını kullanıyor, bazı bilgisayarlarda Powershell'in yetkilendirme hatası nedeniyle Kaynak Koddaki yazılımı "executable" hale getirdim. Yetki hatası almayanlar isterlerse Sorce Kodunu doğrudan kullanabilirler ama pratiklik açısından tavsiye etmem.
Bu yazılım birçok Powershell yöntemini uygulamaya hazırlandığı için yöntemleri öğrenmek isteyenler tarafından da incelenebilecek bir belge niteliğindedir. Nasıl çalıştığını anlamadığınız kısımlar olursa sormakta tereddüt etmeyin.
