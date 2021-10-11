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

`SCRAPING OF URLS WITHIN THE HTML PAGE OF THE COMPLEX URL`

```
 ______  _____      ______  _____ _    _ _______  ______
 |  ____ |     | ___ |     \   |    \  /  |______ |_____/
 |_____| |_____|     |_____/ __|__   \/   |______ |    \_
```````````````````````````````````````````````````````````
https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=sspa_dk_detail_9?ie=UTF8&adId=A01618256LZ954FE1B2B&qualifier=1633927840&id=2301742887845320&widgetName=sp_detail_thematic&url=%2Fdp%2FB01EWOE0UU%2Fref%3Dsspa_dk_detail_9%3Fpsc%3D1%26pd_rd_i%3DB01EWOE0UU%26pd_rd_w%3DgrITa%26pf_rd_p%3D54ed5474-54a8-4c7f-a88a-45f748d18166%26pd_rd_wg%3DYOIjW%26pf_rd_r%3DQ2CEXC6VDKNG7375H211%26pd_rd_r%3D37ca730f-20e2-440a-91b8-6eacd7f3cf25
https://www.amazon.com/gp/slredirect/picassoRedirect.html/ref=sspa_dk_detail_9?ie=UTF8&adId=A01618256LZ954FE1B2B&qualifier=1633927840&id=2301742887845320&widgetName=sp_detail_thematic&url=%2Fdp%2FB01EWOE0UU%2Fref%3Dsspa_dk_detail_9%3Fpsc%3D1%26pd_rd_i%3DB01EWOE0UU%26pd_rd_w%3DgrITa%26pf_rd_p%3D54ed5474-54a8-4c7f-a88a-45f748d18166%26pd_rd_wg%3DYOIjW%26pf_rd_r%3DQ2CEXC6VDKNG7375H211%26pd_rd_r%3D37ca730f-20e2-440a-91b8-6eacd7f3cf25
#
/gp/yourstore/pym/ref=pd_pyml_rhf/139-0214264-8268823
#nav-top
https://www.amazon.jobs
https://blog.aboutamazon.com/?utm_source=gateway&utm_medium=footer&token=about
https://www.aboutamazon.com/?utm_source=gateway&utm_medium=footer&token=about
https://sustainability.aboutamazon.com/?utm_source=gateway&utm_medium=footer&ref_=susty_footer
https://www.amazon.com/pr
https://www.amazon.com/ir
/gp/browse.html?node=2102313011&ref_=footer_devices
https://sell.amazon.com/?ld=AZFSSOA&ref_=footer_soa
https://developer.amazon.com
https://affiliate-program.amazon.com/
https://www.fountain.com/jobs/amazon-delivery-service-partner?utm_source=amazon.com&utm_medium=footer
https://logistics.amazon.com/marketing?utm_source=amzn&utm_medium=footer&utm_campaign=home
https://advertising.amazon.com/?ref=ext_amzn_ftr
/gp/seller-account/mm-summary-page.html?ld=AZFooterSelfPublish&topic=200260520&ref_=footer_publishing
https://www.amazon.com/b/?node=13853235011
/b/?node=18190131011&ld=AZUSSOA-seemore&ref_=footer_seemore
/iss/credit/rewardscardmember?plattr=CBFOOT&ref_=footer_cbcc
/credit/storecard/member?plattr=PLCCFOOT&ref_=footer_plcc
/gp/product/B084KP3NG6?plattr=SCFOOT&ref_=footer_ACB
/dp/B07984JN3L?plattr=ACOMFO&ie=UTF-8
/dp/B07CBJQS16?pr=ibprox&plattr=CCLFOOT&place=camp&ie=UTF-8&ref_=footer_ccl
/gp/browse.html?node=16218619011&ref_=footer_swp
/gp/browse.html?node=3561432011&ref_=footer_ccmp
/gp/browse.html?node=10232440011&ref_=footer_reload_us
/gp/browse.html?node=388305011&ref_=footer_tfx
/gp/help/customer/display.html?nodeId=GDFU3JS5AL6SYHRD&ref_=footer_covid
https://www.amazon.com/gp/css/homepage.html?ref_=footer_ya
https://www.amazon.com/gp/css/order-history?ref_=footer_yo
/gp/help/customer/display.html?nodeId=468520&ref_=footer_shiprates
/gp/prime?ref_=footer_prime
/gp/css/returns/homepage.html?ref_=footer_hy_f_4
/hz/mycd/myx?ref_=footer_myk
/gp/BIT/ref=footer_bit_v2_us_A0029?bitCampaignCode=A0029
/gp/help/customer/display.html?nodeId=508510&ref_=footer_gw_m_b_he
/?ref_=footer_logo
/gp/customer-preferences/select-language/ref=footer_lang?ie=UTF8&preferencesReturnUrl=%2F
/gp/navigation-country/select-country/ref=footer_icp_cp?ie=UTF8&preferencesReturnUrl=%2F
https://music.amazon.com?ref=dm_aff_amz_com
https://advertising.amazon.com/?ref=footer_advtsing_amzn_com
/gp/browse.html?node=15547130011&ref_=_us_footer_drive
https://www.6pm.com
https://www.abebooks.com
https://www.acx.com/
https://www.alexa.com
https://sell.amazon.com/?ld=AZUSSOA-footer-aff&ref_=footer_sell
/business?ref_=footer_retail_b2b
/alm/storefront?almBrandId=QW1hem9uIEZyZXNo&ref_=footer_aff_fresh
/gp/browse.html?node=230659011&ref_=footer_amazonglobal
/services?ref_=footer_services
https://ignite.amazon.com/?ref=amazon_footer_ignite
https://aws.amazon.com/what-is-cloud-computing/?sc_channel=EL&sc_campaign=amazonfooter
https://www.audible.com
https://www.bookdepository.com
https://www.boxofficemojo.com/?ref_=amzn_nav_ftr
https://www.comixology.com
https://www.dpreview.com
https://www.eastdane.com/welcome
https://www.fabric.com
https://www.goodreads.com
https://www.imdb.com
https://pro.imdb.com?ref_=amzn_nav_ftr
https://kdp.amazon.com
/gp/browse.html?node=13234696011&ref_=_gno_p_foot
https://videodirect.amazon.com/home/landing
https://www.shopbop.com/welcome
/gp/browse.html?node=10158976011&ref_=footer_wrhsdls
https://www.wholefoodsmarket.com
https://www.woot.com/
https://www.zappos.com
https://ring.com
https://eero.com/
https://blinkforhome.com/?ref=nav_footer
https://shop.ring.com/pages/neighbors-app
/gp/browse.html?node=14498690011&ref_=amzn_nav_ftr_swa
https://www.pillpack.com
/gp/browse.html?node=12653393011&ref_=footer_usrenew
/amazonsecondchance?ref_=footer_asc
/gp/help/customer/display.html?nodeId=508088&ref_=footer_cou
/gp/help/customer/display.html?nodeId=468496&ref_=footer_privacy
/interestbasedads/ref=footer_iba
/rd/uedata?tepes=1&id=Q2CEXC6VDKNG7375H211
----------------------------- GATHERING CODE NOTES ----------------------
<!-- enxioflkmgm4y5gbyce3yzkv5wn2yysskaykfdx1rqlfnq21rp4a2odq755tjbif7q0lhxr40huu3usk3tqwivykhfnvl8z5ppznnuoybs5vlfzvg8uuq4hshkf1bfk3ol8qyv2jd0p10rmxjee7b7ld5gs6ph5m84v3rdk2dmsftjqh9hhhuxdjllfp7rbs3wx -->
<!-- NAVYAAN CSS -->
<!-- Remote config blank inline CSS -->
<!-- BeginNav -->
<!-- NAVYAAN JS -->
<!--Pilu -->
<!-- NAVYAAN -->
<!-- navmet initial definition -->
<!-- Navyaan Upnav -->
<!-- unw1 failed -->
<!-- Navyaan SWM -->
<!-- nav-linktree-subnav - 'pc' -->
<!-- EndNav -->
<!-- For LightningDeal use case, agsShippingAndIfdInsideBuyBox is only configured on regular offer, so set defaultPageContext as buyingPrice -->
<!-- returnPolicy -->
<!-- productSupportPolicy -->
<!-- Append onload function to stretch image on load to avoid flicker when transitioning from low res image from Mason to large image variant in desktop -->
<!-- any change in onload function requires a corresponding change in Mason to allow it pass in /mason/amazon-family/gp/product/features/embed-features.mi -->
<!-- and /mason/amazon-family/gp/product/features/embed-landing-image.mi -->
<!--Only include showroom templates when the base view adapter is being invoked-->
<!-- considering updating DetailPageDelightPricingTests package whenever you change the template view -->
<!-- Hide shipping message if buying price is shown since that already includes the message -->
<!-- ALM BO bypass is not included in the following SnS use case because SnS is not supported on the ALM platform. This will be addressed when SnS is offered on ALM -->
<!-- if warranty SI is eligible to be shown https://w.amazon.com/bin/view/VAS/Discovery/ServiceInterstitialDisplayLogic-->
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

  
