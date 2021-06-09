# FireAlarm


Merhabalar ben Burhan Göksel. Fırat Üniversitesi Yazılım Mühendisliği bölümünde 3. sınıf dersi olan Mikroişlemciler Ve Proglama dersi için yaptığım projeyi sizler ile paylaşmak istiyorum.

Arduino kullanarak sınıf arkadaşlarım ile bir yangın alarmı tasarladık.

Kullanılan sensörler:
  - Arduino
  - GSM sensörü
  - Wifi Sensörü
  - LM35
  - Gaz sensörü
  - Buzzer
  - RGB

# Proje Adımları

  1 - Gaz sensörü ve sıcaklık sensöründen çalışır. <br>
  2 - Gelen veriler Thingspeak sunucu kullanılarak json veriler post edilir <br>
  3 - Thingspeak de oluşan json veriler kullanılarak android uygulamasına aktarılır. Anlık olarak cihazın konumundaki durum kontrollü yapılabilir. <br>
  4 - Gelen veriler kodda kontrol edilir. Olağan dışı durumlarda buzzer öter ve rgb renk değiştirir. <br>
  
  
Not = Projenin android kodlarını bulamadığım için paylaşamadım. Kısaca android projesinde retrofit2 kullanıldı. Gelen veriler recycleview kullanılar activity üzerinde paylaşıldı.

