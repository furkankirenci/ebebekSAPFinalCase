# ebebekSAPFinalCase

<!-- Projenin Hazırlanışı -->
### Projenin Hazırlanışı

- Bizimle paylaşılan proje Drive üzerinden indirildi.  
- Paylaşılan dosyadaki `installer.bat` dosyasını çalıştırmak için JDK 11 indirildi ve kuruldu.  

<img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_1.png" alt="selection-sort" />

- `Apache Ant` gerekli dosya olan `setantenv.bat` ile kuruldu.  
- `ant clean all` işlemi yapıldı.  
- `Enter` basılarak default olarak başarılı bir şekilde kurulum yapıldı.  
- `installer.bat` çalıştırmak için gerekli komut kullanıldı.
- Başarılı bir şekilde kurulum yapıldı.  

<img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_2.png" alt="selection-sort" />

- SAP'nin sitesindeki kurulum komutları sıralsıyla kullanıldı.
```java
install.bat -r b2c_acc_plus -A local_property:initialpassword.admin=your_password
```
 <img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_6.png" alt="selection-sort" />

```java
install.bat -r b2c_acc_plus initialize -A local_property:initialpassword.admin=your_password
```

 <img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_9.png" alt="selection-sort" />

 ```java
install.bat -r b2c_acc_plus start  
```
- Girilen son komut olan start komutunu kullandığımda cmd üzerinde 2 saatten fazla beklememe rağmen sonuç alamadım.  

 <img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_11.png" alt="selection-sort" />

 - Tüm bu işlemlerin ardından `https://localhost:9002`'ye erişmeyi başardım.  

<img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_13.png" alt="selection-sort" />

<img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_12.png" alt="selection-sort" />

<img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_13.png" alt="selection-sort" />

<img src="https://github.com/furkankirenci/ebebekSAPFinalCase/blob/main/SAP%20Hybris/Screenshot_14.png" alt="selection-sort" />


<!-- CONTACT -->
## Contact

### Furkan Kirenci

<a href="https://github.com/furkankirenci" target="_blank">
<img  src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 20px;" />
</a>
<a href="https://www.linkedin.com/in/furkan-kirenci-912668245/" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 20px; margin-left:20px" />
</a>

<!-- PROJECT-BOOTCAMP-PRACTICUM PART -->
<br />

## ebebek Java & QA & SAP Spartacus Practicum
<div align="center">
  <a href="https://www.e-bebek.com">
    <img src="https://github.com/furkankirenci/ebebekFinalCase/blob/main/images/ebebek-logo.png" alt="Logo" width="200" height="50">
  </a>

<h3 align="center">Company: ebebek</h3>
</div>
<br>
<br><br>
<div align="center">
  <a href="https://www.patika.dev/tr">
    <img src="https://github.com/furkankirenci/ebebekFinalCase/blob/main/images/patika-logo.svg" alt="Logo" width="240" height="50">
  </a>
<h3 align="center">Organizer: Patika.dev</h3>
</div>
