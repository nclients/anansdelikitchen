---
layout: "ssg-theme-astro/layouts/main.astro"  # This line of code should remain unchanged.
tag: "GTM-"
title: "AnAn's Deli Kitchen 安安麵食 - Best Food Today"
favicon: "logo.svg"
logo: "logo.svg"
primaryColor: "#D1D5D4" # logo color
secondaryColor: "#000000"
primaryColorScheme: "light" # dark | light
secondaryColorScheme: "dark"
cuid: ""
ruid: ""
orderOnlineLink: "https://onlineorder.bestfood.today/Restaurant/details/MTAwNDI="
tableReservationLink: ""
tel: "628-588-2246"

# banner:
#   text: 
#     # - boldText: "🥳 Special Offer"
#     - boldText: "20% off cash discount"
#     - text: " on xxx"
#     - smText: ""
#   # add more text...
#   textColor: "#ffffff"
#   bgColor: "#E7383D"
#   bgOpacity: "1" # 0~1

# header
header:
  logoSize: 45
  textAfterLogo: 
    text: "AnAn's Deli Kitchen 安安麵食"
    size: 20
    color: "#000000"
  bgColor: "#ffffff"
  bgOpacity: "0.9" # 0~1
  menuTextColor: "#000000"
  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    # - { text: "About Us", link: "#about-us" }
    - { text: "聯繫我們", link: "#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "在線訂餐"
  otherBtn1Href: "https://onlineorder.bestfood.today/Restaurant/details/MTAwNDI="
  otherBtn2InsteadText: ""
  otherBtn2Href: ""

sections:
# hero
  - type: "hero" 
    id: ""
    height: "90" # Conditionally use only when sectionType is imgBg
    sectionType: "imgBg" # video | imgWithText | imgBg
    bgVideoType: "" # youtube | vimeo | gjw
    bgVideoId: ""
    bgImg: "AnAn's Deli Kitchen 安安麵食.jpg"
    bgColor: "#000000"
    bgOpacity: "0.35" # 0~1
    title: 
      - "AnAn's Deli Kitchen 安安麵食"
    titleColor: "#ffffff"
    description: 
      - "麵條, 拉麵, 湯."
      - "從我們豐盛的台灣牛肉麵到美味的日本慢燉豬骨拉麵，每一道菜品都精心製作，選材講究。探索我們的菜單，發現您新的最愛吧！"
    descriptionColor: "#ffffff"
    # title2: 
    #   - ""
    # title2Color: "#ffffff"
    # description2: 
    #   - ""
    # description2Color: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""

    btn1Text: ""
    btn1Href: "" 
    btn2Text: "" 
    btn2Href: "" 

    bannerImg: ""
    imgPosition: "" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

# # Video
#   - type: "video"
#     id: ""
#     title: 
#       - "Lorem ipsum dolor sit amet"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et" 
#     videoType: "gjw" # vimeo | gjw | youtube
#     videoId: 
#       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
#       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
#     isOnlyDisplayOnMobile: false

# Gallery  
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "美味誘人時刻"
    titleColor: "#000000"
    description: 
      - "我們的菜單提供多樣化的正宗美食，包括台灣牛肉麵、日本拉麵、東北豬肉水餃和美味的煎餅。別忘了嘗試我們受歡迎的拿鐵咖啡和波霸奶茶！"
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: true # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


# # textBlock - only title
#   - type: "textBlock" 
#     id: "about-us"
#     bgImg: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "About Us"
#     titleColor: "#000000"
#     description: 
#       - "A Chinese restaurant ..."
#     descriptionColor: ""

# # feature - imgWithText
#   - type: "feature" 
#     noMarginTop: true
#     id: ""
#     height: "100" # Conditionally use only when sectionType is imgBg
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     title: 
#       - "Lorem ipsum dolor sit ame"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: ""
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""

#     btn1Text: "" 
#     btn1Href: "" 
#     btn2Text: "" 
#     btn2Href: "" 

#     bannerImg: "sample.webp"
#     imgPosition: "imgLeft" # imgLeft | imgRight
#     bannerMarginTopMobile: 20
#     imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# # feature - map
#   - type: "feature" 
#     id: ""
#     noMarginTop: false
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     title: 
#       - "Store 2 : Washington St"
#     titleColor: "#000000"
#     description: 
#       - "Opening Hours: "
#       - "Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: true
#     orderOnlineBtnInsteadText: ""
#     addTableReservationBtn: true
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: true
#     btn1Text: "Order online from Washington St Store" 
#     btn1Href: "#" 
#     btn2Text: "" 
#     btn2Href: "" 

#     map: true
#     url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
#     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
#     addTelBtn: true
#     tel: "12345678"
#     telInsteadText: "Call: (123) 456-7890"
#     tel2: "876543210" # if there are two phone numbers"
#     tel2InsteadText: "Call: (876) 543-2100"
#     getDirectionBtnInsteadText: ""
#     imgPosition: "" # imgLeft | imgRight




# # textBlock 
#   - type: "textBlock" 
#     id: "about-us"
#     bgImg: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "About Us"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"

# textBlock - Information
  - type: "textBlock" 
    noMarginTop: false
    id: ""
    bgImg: "Spices 3 辣妹子 - Best Food Today.webp"
    bgImgAlt: "gallery/豬腩拉麵 Japanese Slow Cook Pork Ramen.webp"
    bgColor: "#000"
    bgOpacity: "1" # 0~1
    title: 
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description: 
      - "現在支援線上訂單自取。只要告訴我們您想要的菜餚，我們會​​盡快準備好。所有訂單都由我們手動確認。您可以即時查看您的食物何時準備好。訂單狀態會即時更新，您可以在螢幕上查看您的食物何時可以取走。"
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/wCyNbCLy16wDMimT6"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.432834153359!2d-122.4960347242445!3d37.77989497198408!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808587633b67090b%3A0x9d63275356723aab!2sAnAn&#39;s%20Deli%20Kitchen!5e0!3m2!1sen!2sjp!4v1722891668538!5m2!1sen!2sjp"
    addTelBtn: true
    tel: ""
    telInsteadText: ""
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: "導航去餐廳"
 
#  # The modal will only appear once within 30 minutes."
#   - type: "modal" 
#     bgColor: "#333"
#     bgOpacity: "0.1" # 0~1
#     title: 
#       - "🎁 Special Offers"
#     titleColor: "#FF2D2F"
#     titleSize: 24
#     description: 
#       - "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     descriptionColor: ""
#     descriptionSize: 16
#     imgName: "special_offer.webp"
#     imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     imgHref: ""
#     buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "店內一角 Interior of AnAns Deli Kitchen.webp"
  bgColor: "#ffffff"
  bgOpacity: "0.85" # 0~1
  textColor: "#000000" # default white

  openingHoursInsteadText: "營業時間"
  openingHours: 
    - "週一 ～ 週日 11:00 AM - 8:45 PM"
  isLogo: false
  logoSize: 60
 
  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    # - { text: "About Us", link: "#about-us" }
    - { text: "聯繫我們", link: "#contact-us" }
    - { text: "English", link: "/" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""

  acceptedPaymentMethodsInsteadText: ""
  paymentMethod: "" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  # at a minimum, please make sure to include the meta description.
  seo:
    metaDescription: "发现位于旧金山的 AnAn's Deli Kitchen 安安麵食，体验卓越的用餐享受。快來餐廳品嚐，现在就在线下單吧！" 
    keywords: ""
    img: ""
    thisPageUrl: ""
    locale: "zh_TW" # zh_TW | zh_CN
---
<!-- hello world -->