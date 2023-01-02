

---

### Nasıl kullanılır
- **JAVA** öğrenin
- Gizleme/bytecode/re hakkında biraz bilgi edinin *(İsteğe bağlı)*

Bu kod gizleme aracı herhangi bir **gui** veya **yapılandırma dosyası** sağlamaz çünkü bir **IDE**.\
Deobfuscator'ı tercihlerinize göre yapılandırmak için **Loader** sınıfını düzenlemeniz gerekir.

- https://github.com/narumii/Deobfuscator#transformers

---

### Desteklenen Obfuscator

- [superblaubeere27 / JObf / sb27](https://github.com/superblaubeere27/obfuscator)
- [Paramorfizm 2.1.2_9](https://paramorphism.dev/)
- [Sezyum](https://github.com/sim0n/Caesium)
- [Monsey](https://github.com/Hippo/Mosey)
- [(Skid)q~~Koru~~ (Son Değil)](https://mdma.dev/)
- [Scuti](https://github.com/netindev/scuti)
- [CheatBreaker](https://github.com/CheatBreaker/Obf)
- [Bozar](https://github.com/vimasig/Bozar)
- [ZKM 11 Den önce](https://www.zelix.com/klassmaster/featuresZKMScript.html)
- **RakSzild**: HackShield'da kullanılan bazı aptal cilalı karartıcı
- **HP888**: EyfenCord/SafeMC'de kullanılan bazı aptal cilalı karartıcı v2

### Kısmen Desteklenen Gizleyiciler
- [Binsecure 0.4/Latest](https://binclub.dev/purchasing/)
- [(Skid)q~~Koru~~](https://mdma.dev/)
- [Radon](https://github.com/ItzSomebody/radon)
- Sömürge
- Nöbetçi


---

### Transformatörler
> Kod gösterme hakkında hiçbir şey bilmiyorsanız **önceden oluşturulmuş** olanları kullanın\
> Transformatörlerin çoğu çerçevesiz yapılır, bu nedenle bazen çalışmayabilirler
- [Bazı karartıcılar için önceden oluşturulmuş transformatörler](https://github.com/narumii/Deobfuscator/tree/master/src/main/java/uwu/narumi/deobfuscator/transformer/composed)
- [Mevcut tüm transformatörler](https://github.com/narumii/Deobfuscator/tree/master/src/main/java/uwu/narumi/deobfuscator/transformer/impl)

---

### SandBox çalışmıyor

> Jvm bağımsız değişkenlerine `-noverify` ekleyin, eğer hala çalışmıyorsa sorunu açın

![](https://i.imgur.com/PBCQ6iO.png)

---

> Deobfuscator, kodu yalnızca insanlar için okunabilir hale getirir, ayrıca bazı derleyiciler sınıfı kaynak koda dönüştüremezse başka birini deneyin ve hiç kimse çalışmazsa, yalnızca şunları içeren bir sorun oluşturun: `[gizleme, deobfuscator transformatörleri, deobfuscator günlük dosyası]` ve isteğe bağlı obfuscator adı

---

> Built on: [Java 11 (Adoptium)](https://adoptium.net/temurin/releases/?version=11)
