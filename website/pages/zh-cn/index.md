---
layout: "ssg-theme-astro/layouts/main.astro" # This line of code should remain unchanged.
tag: ""
title: "AnAn's Deli Kitchen 安安麵食 - Best Food Today"
favicon: "anan.ico"
logo: "logo.png"
primaryColor: "#C2232E" # logo color
secondaryColor: "#F2E0D9"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: ""
cuid: ""
ruid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=229221c8-8e50-4b68-9841-f77b2b1a5d6e"
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
  logoSize: 100
  logoSizeOnMobile: 90
  textAfterLogo:
    text: ""
    size: 20
    color: "#000000"
  bgColor: "#ffffff"
  bgOpacity: "0.9" # 0~1
  menuTextColor: "#000000"
  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "關於我們", link: "#about-us" }
    - { text: "聯繫我們", link: "#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "在線訂餐"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=229221c8-8e50-4b68-9841-f77b2b1a5d6e"
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
    bgOpacity: "0.6" # 0~1
    title:
      - "AnAn's Deli Kitchen"
      - "安安麵食"
    titleColor: "#ffffff"
    description:
      - "麵條、拉麵、湯"
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

    btn1Text: "在線訂餐"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=229221c8-8e50-4b68-9841-f77b2b1a5d6e"
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

  # textBlock
  - type: "textBlock"
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "關於我們"
    titleColor: "#000000"
    description:
      - "歡迎來到AnAn's Deli Kitchen 安安麵食，這裡是您在舊金山外里士滿街區享用正宗美味中餐的首選目的地。位於 Geary Blvd 6900 號，我們專注於各種傳統菜餚。我們熱衷於提供採用最優質食材製成的高品質手工菜餚。我們乾淨溫馨的空間旨在為您提供舒適的用餐體驗，您可以在這裡享用我們的美味佳餚。無論您是來品嚐一碗豐盛的拉麵、美味的餃子還是甜點，我們都致力於為您提供美味佳餚。"
  #     descriptionColor: "#000000"

  # textBlock - Information
  - type: "textBlock"
    noMarginTop: false
    id: ""
    # bgImg: "/拿鐵奶咖啡 Latte Coffee.webp"
    # bgImgAlt: "拿鐵奶咖啡 Latte Coffee.webp"
    bgColor: "#000"
    bgOpacity: "1" # 0~1
    title:
      - "新功能！在線訂餐"
    titleColor: "#ffffff"
    description:
      - "現在支援線上訂單自取。只要告訴我們您想要的菜餚，我們會​​盡快準備好。所有訂單都由我們手動確認。您可以即時查看您的食物何時準備好。訂單狀態會即時更新，您可以在螢幕上查看您的食物何時可以取走。"
    descriptionColor: "#ffffff"

  # map
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/vPhwgQCF3uowqNrYA"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.432834153387!2d-122.49603472378126!3d37.779894971984156!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808587633b67090b%3A0x9d63275356723aab!2sAnAn&#39;s%20Deli%20Kitchen!5e0!3m2!1szh-TW!2sus!4v1725374402309!5m2!1szh-TW!2sus"
    addTelBtn: true
    tel: ""
    telInsteadText: "電話：628-588-2246"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: "前去餐廳"

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
  bgColor: "#000"
  bgOpacity: "0.8" # 0~1
  textColor: "#fff" # default white

  openingHoursInsteadText: "營業時間"
  openingHours:
    - "週一 ～ 週日"
    - "11:00 AM - 8:45 PM"
  isLogo: false
  logoSize: 60

  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "關於我們", link: "#about-us" }
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

  acceptedPaymentMethodsInsteadText: "支付方式"
  paymentMethod: "cash,visa,amex,alipay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "AnAn's Deli Kitchen 安安麵食 | 舊金山里士滿區的正宗中餐"
  metaDescription: "在舊金山里士滿區的AnAn's Deli Kitchen 安安麵食，品嚐手工製作的拉麵、餃子和甜點，享受舒適的用餐環境。"
  keywords: ""
  img: ""
  canonicalHref: "https://anansdelikitchen.com/zh-cn/" # https://example.com/
  locale: "zh_CN" # zh_TW | zh_CN
---

<!-- hello world -->
