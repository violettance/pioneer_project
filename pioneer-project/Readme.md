
Hocam merhaba,

Benim Xcode'umda custom fontlar uninstall gözüküyordu, ben de Apple'ın documentation'ına baktım "Adding a Custom Font to Your App" kısmında yazılanları tek tek yaptım, son olarak info.plist içinde düzeltmelerimi de yaptıktan sonra olması gerekiyordu lakin herhangi bir font bulunamadı. Ben de "Contact" kısmı içindeki başlıklarda farklı bir font kullanmak istediğim için online font changer kullanarak yazı fontunu değiştirip koydum. Uygulamayı çalıştırdığımda şu şekilde bir uyarı alıyorum Xcode'u kızdırdım sanırım, lakin programın çalışmasına engel olmadığı için değiştirmemeye karar verdim. 


UYARI = 2021-01-12 15:16:27.401879+0300 pioneer-project[53072:4767102] CoreText note: Client requested name ".PingFangSC-Regular", it will get TimesNewRomanPSMT rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[UIFont systemFontOfSize:].
2021-01-12 15:16:27.402184+0300 pioneer-project[53072:4767102] CoreText note: Set a breakpoint on CTFontLogSystemFontNameRequest to debug.
