
# 𝕄𝕠𝕕𝕖𝕣𝕟 𝕎𝕖𝕓 𝔸𝕡𝕡 ℙ𝕣𝕠𝕛𝕖𝕔𝕥 𝟚𝟘𝟚𝟚 𝕨𝕚𝕥𝕙 𝕀𝕞𝕡𝕣𝕠𝕧𝕖𝕞𝕖𝕟𝕥𝕤 𝕒𝕟𝕕 ℙ𝕖𝕣𝕗𝕠𝕣𝕞𝕒𝕟𝕔𝕖𝕤 𝕗𝕠𝕣 𝕥𝕙𝕖 𝔹𝕖𝕤𝕥 𝕌𝕤𝕖𝕣 𝔼𝕩𝕡𝕖𝕣𝕚𝕖𝕟𝕔𝕖.




![Captura de pantalla de 2022-08-17 18-05-00](https://user-images.githubusercontent.com/97669969/185188966-62231495-c2cd-4cc8-b646-1708e2a03eef.png)


![Captura de pantalla de 2022-08-17 18-05-26](https://user-images.githubusercontent.com/97669969/185188988-c8d41534-af87-41f3-b831-55328f620f2a.png)


![Captura de pantalla de 2022-08-17 18-05-40](https://user-images.githubusercontent.com/97669969/185189016-06d9e126-a7e6-4650-a696-829ece48760d.png)



![Captura de pantalla de 2022-08-17 18-05-52](https://user-images.githubusercontent.com/97669969/185189029-c28a4aa9-67df-4b3c-b8a8-122e30511b9f.png)



![Captura de pantalla de 2022-08-17 18-06-11](https://user-images.githubusercontent.com/97669969/185189045-b9c343b6-72eb-4fde-b835-e29ca1f0ab57.png)


![Captura de pantalla de 2022-08-17 18-06-25](https://user-images.githubusercontent.com/97669969/185189059-064b167f-1fa1-44d0-8c99-00149bba180a.png)


![Captura de pantalla de 2022-08-17 18-06-45](https://user-images.githubusercontent.com/97669969/185189073-fe5be32b-9c99-4f2f-8326-25e5a515b870.png)








https://user-images.githubusercontent.com/97669969/185189254-521f6087-0113-46c4-b689-23387424b9f7.mp4



## 𝕃𝕚𝕧𝕖: https://blogdelvino-tmcyber.netlify.app/





## 𝕎𝕙𝕒𝕥 𝕞𝕒𝕜𝕖𝕤 𝕒 𝕄𝕠𝕕𝕖𝕣𝕟 𝕎𝕖𝕓, 𝕥𝕒𝕜𝕚𝕟𝕘 𝕚𝕟𝕥𝕠 𝕒𝕔𝕔𝕠𝕦𝕟𝕥 𝕟𝕠𝕥 𝕠𝕟𝕝𝕪 𝕥𝕙𝕖 𝕒𝕡𝕡𝕖𝕒𝕣𝕒𝕟𝕔𝕖?

 *  🅃🄷🄴 🄼🄾🄳🄴🅁🄽 🄿🅁🄾🄶🅁🄰🄼🄼🄸🄽🄶 🅂🄺🄸🄻🄻🅂 🄾🄵 🄴🅅🄴🅁🅈 🄳🄴🅅🄴🄻🄾🄿🄴🅁


# Ｐｅｒｆｏｍａｎｃｅ ＇Ｗｅｂ／Ａｐｐ ｉｎ ｔｈｉｓ Ｐｒｏｊｅｃｔ＇ｅｒ


## ℍ𝕋𝕄𝕃 '𝔸𝕔𝕔𝕖𝕤𝕚𝕓𝕚𝕝𝕚𝕥𝕪 𝕨𝕖𝕓' 

##### Web prepared for:
 
* Older and disabled persons, with assistive devices (voice assistance)
* People who have certain problems to move the mouse well.



## ℍ𝕋𝕄𝕃 𝕃𝕠𝕒𝕕𝕚𝕟𝕘 "𝕝𝕒𝕫𝕪"

* Download images as needed is reducing the load on the server, if there were 20 30 40 images are not all loaded at time.
* They are loaded as the page is scrolled by the user.


## ℍ𝕋𝕄𝕃 'ℙ𝕣𝕖𝕝𝕠𝕒𝕕'

* Stylesheet/css, fonts, etc, should be loaded as soon as possible, making a good experience when users are using our web/app.



## ℍ𝕋𝕄𝕃 'ℙ𝕣𝕖𝕗𝕖𝕥𝕔𝕙' 

* What page do we want to load as soon as possible?
* To know on which page to apply prefetch, I recommend: Google Analytics.
* We first need to know which page users spend the most time on, and then prefetch that page.


## 𝕎𝕖𝕓ℙ '𝔽𝕠𝕣𝕞𝕒𝕥"

* Using webp format, the load is very faster.
* Let say we use .jpg size 6 mb and webp with size 3mb, webp would almost always be half, there are exceptions, and surely is more faster.

* But webp is not yet 100% supported in all browsers, like safari, but don't worry i have the key-->

```bash

 <picture>
              <source srcset="img/blog1.jpg" type="image/webp" />
              <img loading="lazy" src="img/blog1.jpg" alt="imagen blog" />
            </picture>
            
```
			

**Label structure that in the case of not loading by webp, it would go to the next one, which would be the jpg.**			
			
			
## 𝕄𝕠𝕕𝕖𝕣𝕟𝕚𝕫𝕣 '𝕎𝕖𝕓𝕡 𝕗𝕠𝕣𝕞𝕒𝕥'

* https://modernizr.com/

* Javascript library for Webp format.
			



##𝕄𝕖𝕥𝕒 '𝕋𝕒𝕘𝕤'

```bash

<meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Blog del Cafe</title>
    <meta name="description" content="Pagina web de blog de cafe" />
    
```




#ℍ𝕖𝕣𝕖’𝕤 𝕒 𝕝𝕚𝕤𝕥 𝕠𝕗 𝕤𝕠𝕞𝕖 𝕠𝕗 𝕥𝕙𝕖 𝕞𝕠𝕤𝕥 𝕡𝕠𝕡𝕦𝕝𝕒𝕣 𝕦𝕤𝕖𝕤 𝕠𝕗 𝕥𝕙𝕚𝕤 𝕨𝕖𝕓 𝕥𝕠𝕕𝕒𝕪:




* eCommerce website

* Business website

* Blog website

* Portfolio website

* Event website

* Personal website

* Membership website

* Nonprofit website

* Informational website

* Online forum





# 𝕎𝕖𝕓𝕤𝕚𝕥𝕖 𝔽𝕦𝕝𝕝𝕪 ℝ𝕖𝕤𝕡𝕠𝕟𝕤𝕚𝕧𝕖:

* All Ipads
* All Mobiles 
* All Macbooks (air, pro, retina, etc)
* All Generic Laptop
* All Iphones
* All Nexus
* All Galaxy
* All Kindle
* All Blackberry
* All 4K, 5K, 8K Displays
* All Surface
* Etc



# 𝔹𝕣𝕠𝕨𝕤𝕖𝕣 ℂ𝕠𝕞𝕡𝕒𝕥𝕚𝕓𝕚𝕝𝕚𝕥𝕪 (ℍ𝕚𝕘𝕙-𝔾𝕣𝕒𝕕𝕖)

####Ｈｅｒｅ ａｒｅ ｊｕｓｔ ｓｏｍｅ ｏｆ ｔｈｅｍ ｏｎｌｙ －－>



* Microsoft IE 5.01+
* Netscape Communicator 4.7+
* Mozilla Firefox 1.0+
* Mozilla Suite 1.0+
* AOL 5+
* Opera 7+
* Apple Safari 1.0+
* Red Hat Linux Konqeror
* Sony Playstation
* Microsoft WebTV
* Google Chrome
* Apple Safari
* Kingpin browser
* Tor browser
* Iridium browser
* etc

# 𝕊𝕔𝕣𝕠𝕝𝕝 𝕊𝕟𝕒𝕡 ℙ𝕣𝕖𝕡𝕒𝕣𝕖𝕕

¿ʇɐɥM


#### CSS Scroll Snap is a module of CSS that introduces scroll snap positions, which enforce the scroll positions that a scroll container's scrollport may end at after a scrolling operation has completed.



# 𝕊𝔼𝕆 ℝ𝕖𝕒𝕕𝕪

### Why having an SEO Ready™ website is so important?
To a business, any size or type of website is an investment. Not having your business website built correctly from the beginning will result in a complete waste of time and money. It’s like building a restaurant in the middle of nowhere or printing flyers that will never be mailed.

Fact: If your website does not have the right content strategy or has not been originally programmed and built based on the latest search engine optimization techniques, it will be placed at the bottom of the pile.

Don’t just get a website, get an SEO Ready™ website that will gain the right positioning and visibility at the major search engines like Google™, Bing™, Yahoo™ and Ask.com™.

### 𝔽𝕒𝕔𝕥: 𝔸𝕝𝕝 𝕞𝕪 𝕨𝕖𝕓𝕤𝕚𝕥𝕖𝕤 𝕒𝕣𝕖 𝕓𝕦𝕚𝕝𝕥 𝕊𝔼𝕆 ℂ𝕠𝕞𝕡𝕝𝕚𝕒𝕟𝕥, ℝ𝕖𝕒𝕕𝕪 𝕒𝕟𝕕 ℂ𝕖𝕣𝕥𝕚𝕗𝕚𝕖𝕕™ 𝕣𝕚𝕘𝕙𝕥 𝕗𝕣𝕠𝕞 𝕥𝕙𝕖 𝕤𝕥𝕒𝕣𝕥! 𝕀 𝕕𝕖𝕝𝕚𝕧𝕖𝕣 𝕥𝕙𝕖 𝕓𝕖𝕤𝕥 𝕠𝕗 𝕥𝕙𝕖 𝕝𝕒𝕥𝕖𝕤𝕥 𝕥𝕖𝕔𝕙𝕟𝕠𝕝𝕠𝕘𝕪 𝕚𝕟 𝕨𝕖𝕓𝕤𝕚𝕥𝕖 𝕕𝕖𝕧𝕖𝕝𝕠𝕡𝕞𝕖𝕟𝕥, 𝕤𝕖𝕔𝕦𝕣𝕚𝕥𝕪, 𝕦𝕤𝕒𝕓𝕚𝕝𝕚𝕥𝕪 𝕒𝕟𝕕 𝕤𝕖𝕒𝕣𝕔𝕙 𝕖𝕟𝕘𝕚𝕟𝕖 𝕔𝕠𝕞𝕡𝕒𝕥𝕚𝕓𝕚𝕝𝕚𝕥𝕪.


#### 🅸🅵 🆃🅷🅸🆂 🅿🆁🅾🅹🅴🅲🆃 🅷🅴🅻🅿 🆈🅾🆄 🆁🅴🅳🆄🅲🅴 🆃🅸🅼🅴 🆃🅾 🅳🅴🆅🅴🅻🅾🅿, 🆈🅾🆄 🅲🅰🅽 🅶🅸🆅🅴 🅼🅴 🅰 🅲🆄🅿 🅾🅵 🅲🅾🅵🅵🅴🅴 :)




<a href="https://www.buymeacoffee.com/tonymerisan" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>


[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/E1E1EBFQ3)
