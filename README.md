## Assignment Questions and My Implementations
This project is based on the 4 assignment questions given by the instructor. The original code provided by the instructor had some parts left empty or incomplete.

Below are the 4 questions, followed by the explanation that I implemented the missing parts by writing the code myself to complete the assignment requirements.

## Question 1
Basit komutların çalıştırılabilmesi için gerekli eklemeyi yapınız. Ekleme yapmanız gereken yer yorum satırı olarak belirtilmiştir (Satır 68). Kodunuzu test etmek için basit komutlar kullanabilrsiniz (pwd vs.).

## Question 2
Girdi/çıktı içeren komutlar için gerekli eklemeyi yapınız. Ekleme yapmanız gereken yer yorum satırı olarak belirtilmiştir (Satır 77). Kodda bulunan parser “>” ve “<” işaretlerini tanıyarak redircmd yapısı oluşturmaktadır. Eklemenizden sonra aşağıdaki test komutunun halen doğru şekilde çalışıyor olduğundan emin olunuz.
      echo "Operating Systems" > output.txt
      cat < output.txt

## Question 3
 Sıralı komutları çalıştıracak eklemeyi gerçekleştiriniz. Ekleme yapmanız gereken yer yorum satırı olarak belirtilmiştir (Satır 86). Kodda bulunan parser “|” işaretini tanıyarak pipecmd yapısı oluşturmaktadır. Kodunuzu aşağıdaki komut ile test edebilirsiniz.
ls | sort | wc

## Question 4
Yukarıda gerçekleştirilen özelliklerden yola çıkarak parser’ınızın “&” karakterini tanıyarak paralel prosesler oluşturarak gönderilen argümanlarla gerekli işlemleri paralel olarak yapmasını sağlayan kodu entegre ediniz. Ekleme yapmanız gereken yer yorum satırı olarak belirtilmiştir satır(91). Kodunuzu aşağıdaki örnek komut ile test edebilirsiniz***.
ls &
