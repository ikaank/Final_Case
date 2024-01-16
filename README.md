# Final_Case
Erciyes Anadolu Holding ABAP Bootcamp - Final Case
## Employees & Projects
Proje kapsamında bir işyerinde çalışan bilgilerinin tutulduğu bir header ve çalışanların katıldıkları projelerin bilgilerinin tutulduğu bir item tablosu bulunmaktadır. Çalışan ve proje verileri kullanıcıdan bir Excel dosyası yardımıyla alınmaktadır. Bu Excel şablonunda Project Status alanı kullanı tarafından girilmeyecek, programda tanımlanmış bir butona tıklanınca otomatik olarak hesaplanacak ve iki tablonun da güncel halleri birleştirilerek ALV raporunda bütün verilerin görünmesi sağlanacaktır. 

<br/>
<div>
  
![1 2](https://github.com/ikaank/Final_Case/assets/112203026/62b22f3f-6b09-4b8a-86a3-b48425c30fe0)<br/> 

<div align="center"><p><strong>View Recorded Data</strong></p> </div>
Yukarıda program çalıştırıldıktan sonra bizi ilk karşılayan ekranı görüyoruz. 
</div>

<br/>
<div>
  
![2](https://github.com/ikaank/Final_Case/assets/112203026/2df0786c-dbda-406d-b8f2-050920b6f8e1) <br/>
<div align="center"><p><strong>View/Upload Excel Data</strong></p> </div>

</div>

<br/>
<div>
  
![3](https://github.com/ikaank/Final_Case/assets/112203026/633cfd36-9218-4dc5-8112-816fb37973c6)<br/>
<div><p>Eğer iki alanda doğru bilgilerle doldurulur ise girilen değerlere göre ilgili tablolardan ilgili veriyi getirecektir. Bu veriler bir ALV raporunda gösterilecektir. Birbiriyle eşleşmeyen değerler
veya eksik değer girildiğinde ise aşağıdaki mesajlar gösterilecektir.</p> </div>

</div>

<div>
  
![m1](https://github.com/ikaank/Final_Case/assets/112203026/e89af4cb-5c3e-4111-b800-7b36579cd6a9)
![m2](https://github.com/ikaank/Final_Case/assets/112203026/e4224166-962f-49f2-b7e5-b0ea26e2ea9d)


</div>

<br/>
<div>

<div align="center"><p>Program yukarıdaki mesajlardan hiç birini almamışsa aşağıdaki gibi ilgili veriyi ALV reporunda göstecektir.</p> </div>

![12](https://github.com/ikaank/Final_Case/assets/112203026/5f154564-db22-4c9e-96c9-68c5e6eaf66d) <br/>
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>

</div>

<br/>
<div>

![4](https://github.com/ikaank/Final_Case/assets/112203026/7d704146-f136-4360-a7e5-c6222f6a1716) <br/>
<div><p>Excel dosyası boş ise ALV raporu açılacak ve tabii ki  aşağıdaki gibi boş bir rapor olarak görünecektir.</p> </div>

![5](https://github.com/ikaank/Final_Case/assets/112203026/7b88782f-3b8f-44d3-b89b-1537ae1c0166)
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>

</div>

<br/>
<div>

![7](https://github.com/ikaank/Final_Case/assets/112203026/176fe1a4-b42e-4a73-aaee-fd12041f6cfa) <br/>
<div><p>Excel dosyası dolu ise ALV raporunda Excel dosyasındaki bütün verileri görüntüleyeceğiz. Upload butonuna tıklanırsa veriyi Excel'den veri tabanına çekeceğiz.</p> </div>

![alv buton2](https://github.com/ikaank/Final_Case/assets/112203026/73dc9fc3-6c75-4413-9e80-deef7d9a8c9f)
<div><p>Excel dosyasının boş veya dolu olduğu Upload butonuna tıklayınca sistem tarafında algılanıp eğer dolu ise kaydetme işlemi gerçekleşir.</p> </div>

![m4](https://github.com/ikaank/Final_Case/assets/112203026/f66bebfd-18d5-45a6-b31a-2a197ea49f58)
![m5](https://github.com/ikaank/Final_Case/assets/112203026/970c4c18-891a-4f1f-bb71-049aafc70881)
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>

</div>

<br/>
<div>

![9](https://github.com/ikaank/Final_Case/assets/112203026/fe11455f-b5e5-40e9-96f5-dda6a292f54b)
![10](https://github.com/ikaank/Final_Case/assets/112203026/a8b15e94-21a7-44f4-8ef4-96e600a767cf)
<div><p>Upload butonunun sağındaki iki butondan biri bize Employee tablosunun bakım ekranını açacaktır diğeri ise Project tablosunun bakım ekranını açacaktır. Yukarıda bu ekranların nasıl göründüklerini
görebiliriz.</p> </div>

</div>

<br/>
<div>

<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>
<div><p>Ana ekrandaki Update Project Status butonuna tıklandığında veri tabanına kaydedilmiş verilerin tarih bilgisine göre projenin şimdiki durumunu(aktif,tamamlanmış vs.) hesaplayıp
  bütün verileri ALV raporunda gösterir. Download Excel Template butonu ise kullanıcının elindeki verileri işleyebileceği bir Excel şablonu indirir. Aşağıda sırasıyla bu butonlara tıklanınca
karşımıza gelen ekranları görebiliriz.</p> </div>

![8](https://github.com/ikaank/Final_Case/assets/112203026/cd02ab58-688a-40de-963d-41716dab168f) <br/>
<div><p><strong>-------------------------------------------------------------------------------------------------------------------------------------------------------------</strong></p> </div>

![13](https://github.com/ikaank/Final_Case/assets/112203026/7e149064-588b-4d47-93bc-187ba8f8394b)

</div>


















