# Go-Diver
Dive into the deep realms of html with go-diver for complex URL's

this is a very simple tool written in golang with only one main file, this will crawl all possible URL's within the HTML divs and even gather the code notes<br>
<br>
`THERE ARE NO USER INPUTS OR ARGS YOU WILL NEED TO DEFINE THE URL YOURSELF`
  
there are a few downsides to this script ( its just a fun project i started XD )<br>
1: You have to define thr URL Yourself 
2: you have to go get everything 

`INSTALLS`<br>
`git clone https://github.com/ArkAngeL43/Go-Diver.git ; cd Go-Diver ; go get github.com/PuerkitoBio/goquery ; go get github.com/logrusorgru/aurora ; clear ; go run crawl.go`


`WHAT IT WILL/CAN DO`

```
====================== PARSING OF THE URL ======================

 ______  _____      ______  _____ _    _ _______  ______
 |  ____ |     | ___ |     \   |    \  /  |______ |_____/
 |_____| |_____|     |_____/ __|__   \/   |______ |    \_
```````````````````````````````````````````````````````````
[+] Starting Go Diver....
-------------------------- URL PARSED -------------- 
Scheme        --->  https
Hostname      --->  www.amazon.com
Path in URL   --->  /AURSINC-Deauther-Wristband-Development-Wearable/dp/B08YX7FGZC/
Query Strings --->  _encoding=UTF8&pd_rd_w=GfMya&pf_rd_p=628b38b6-dbee-442c-9e9c-e8813ea9e367&pf_rd_r=XSAEDMNF8YA0CMAFXQX1&pd_rd_r=23e976a4-6fb9-4e02-8641-ba206fe373fb&pd_rd_wg=S3m1q&ref_=pd_gw_ci_mcx_mr_hp_d
Fragments     --->  
-------------- URL QUERY VALS ----------------------- 
map[_encoding:[UTF8] pd_rd_r:[23e976a4-6fb9-4e02-8641-ba206fe373fb] pd_rd_w:[GfMya] pd_rd_wg:[S3m1q] pf_rd_p:[628b38b6-dbee-442c-9e9c-e8813ea9e367] pf_rd_r:[XSAEDMNF8YA0CMAFXQX1] ref_:[pd_gw_ci_mcx_mr_hp_d]]
```

`SCRAPING OF URLS WITHIN THE HTML PAGE OF THE COMPLEX URL`<br>

```
====================== PARSING OF THE HTML NOTES ======================

 ______  _____      ______  _____ _    _ _______  ______
 |  ____ |     | ___ |     \   |    \  /  |______ |_____/
 |_____| |_____|     |_____/ __|__   \/   |______ |    \_
```````````````````````````````````````````````````````````
<!--  Loading EDP related metadata -->
<!--giftCardHolidayAvailabilityMessaging_placeholder-->
<!-- MarkAF -->
<!--CardsClient-->
<!--CardsClient-->
<!-- We want to load our vwdp assets when all the critical features becomes interactive on dp page-->
<!--if there are no critical features, then promise will be undefined-->
<!--TODO: Replace this string with arp-x-ratings 5/22/19 (ShopperExp-5143)-->
<!--CardsClient-->
<!-- NAVYAAN FOOTER START -->
<!-- WITH MOZART -->
<!-- NAVYAAN FOOTER END -->


```

  
