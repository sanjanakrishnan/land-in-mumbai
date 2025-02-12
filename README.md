[# English](https://github.com/sanjana-krish/land-in-mumbai/blob/main/README.md#land-ownership-and-occupation-mumbais-contested-cityscape)

[# हिंदी](https://github.com/sanjana-krish/land-in-mumbai/blob/main/README.md#%E0%A4%9C%E0%A4%AE%E0%A5%80%E0%A4%A8-%E0%A4%95%E0%A5%87-%E0%A4%AE%E0%A4%BE%E0%A4%B2%E0%A4%BF%E0%A4%95-%E0%A4%94%E0%A4%B0-%E0%A4%A8%E0%A4%BF%E0%A4%B5%E0%A4%BE%E0%A4%B8%E0%A5%80-%E0%A4%AE%E0%A5%81%E0%A4%82%E0%A4%AC%E0%A4%88-%E0%A4%95%E0%A5%87-%E0%A4%B5%E0%A4%BF%E0%A4%B5%E0%A4%BE%E0%A4%A6%E0%A4%BF%E0%A4%A4-%E0%A4%B8%E0%A5%8D%E0%A4%A5%E0%A4%B2)

[# मराठी](https://github.com/sanjana-krish/land-in-mumbai/blob/main/README.md#%E0%A4%9C%E0%A4%AE%E0%A5%80%E0%A4%A8-%E0%A4%AE%E0%A4%BE%E0%A4%B2%E0%A4%95-%E0%A4%86%E0%A4%A3%E0%A4%BF-%E0%A4%B0%E0%A4%B9%E0%A4%BF%E0%A4%B5%E0%A4%BE%E0%A4%B8%E0%A5%80-%E0%A4%AE%E0%A5%81%E0%A4%82%E0%A4%AC%E0%A4%88%E0%A4%A4%E0%A5%80%E0%A4%B2-%E0%A4%B5%E0%A4%BE%E0%A4%A6%E0%A4%97%E0%A5%8D%E0%A4%B0%E0%A4%B8%E0%A5%8D%E0%A4%A4-%E0%A4%9C%E0%A4%BE%E0%A4%97%E0%A4%BE)


# Land ownership and occupation: Mumbai's contested cityscape 

## Introduction
52% of Mumbai lives in informal srttlements (or slums) (Census 2011). However, it is not easy to find information on who owns land and what the property records show. This map visualises information on settlement clusters and their ownership. 

## Mapping objectives

- WHAT: Land ownership and occupation
- WHERE: Mumbai, India 
- WHEN: I have data from government sources for 2016 and 2020 (and have some data for additional years 2000 and 2012)
- WHY: 
  - More than half the city stays in informal settlements built by people left out of the unaffordable formal housing sector on land owned (mostly) by the government (but different levels and bodies) or by private builders. To beautify the city and take over the land, informal houses are routinely demolished.
  - However, information on who (specifically which body of the government) ‘owns’ land  is not easy to find. This is important information because the scope for rehabilitation and compensation depends on the land you are on. For example, if it is on state government land, people residing on it have more protection. However, if it is on forest or railway department land, there is no compensation. Similarly, while applying for basic services like water or electricity, land ownserhip needs to be known. Knowing who owns the land that the informal settlement occupies will be useful information for people living there and for activists working on this. 
  - The map visualizes and exposes resource distribution in the city by showing land ‘occupation’ (specifically what the government deems as illegal informal housing) and ‘ownership’ suoerimposed on one another. 
  - This map also helps see the errors in the government's mapping of the slum. The boundaries of slums as drawn by the government often differ from reality because the government fails to capture it. People staying in informal settlements have less claim to land when they are 'uncounted' and 'invisibilized' in official datasets. Through this map, inconsistencies can be found and raised with the authorities to correct the official maps (though there is an issue of the date. 
  - This map is also be useful for academics who want to understand this data

Features
- Toggling between languages (Hindi, Marathi, and English)
- Local search (search settlements by using the search bar)

## Data sources and Methodology

1. Land ownership- data from the Municipal Corporation of Greater Mumbai, data as of October 2020. 
2. Informal settlement clusters- map created by the Slum Rehabilitation Authority in 2016
3. Satellite Map tiles from Leaflet

## Technology stack

- R, QGIS and Map shaper for data cleaning and processing
- Data stored as geoJSONs and TopoJSONs- data storage
- JS for creating the map, using JS libraries such as Leaflet, Papa Parse
- HTML, CSS
- Leaflet base tiles for satellite images.
- Github pages for hosting

-------

# जमीन के मालिक और निवासी: मुंबई के विवादित स्थल

## परिचय
मुंबई का 52% बस्तियों में रहता है (जनगणना 2011)। हालांकि, जमीन का मालिक कौन है और संपत्ति के रिकॉर्ड क्या दिखाते हैं, इस बारे में जानकारी प्राप्त करना आसान नहीं है। यह नक्शा बंदोबस्त समूहों और उनके स्वामित्व के बारे में जानकारी की कल्पना करता है।

## मानचित्रण उद्देश्यों

- क्या: भूमि का स्वामित्व और व्यवसाय
- कहा पे: मुंबई, भारत
- WHEN: मेरे पास 2016 और 2020 के लिए सरकारी स्रोतों से डेटा है (और अतिरिक्त वर्ष 2000 और 2012 के लिए कुछ डेटा है)
- क्यों:
   - आधे से अधिक शहर सरकार (लेकिन विभिन्न स्तरों और निकायों) या निजी बिल्डरों द्वारा स्वामित्व वाली (ज्यादातर) भूमि पर अप्रभावी औपचारिक आवास क्षेत्र से बाहर रह गए लोगों द्वारा निर्मित अनौपचारिक बस्तियों में रहता है। शहर को सुंदर बनाने और जमीन पर कब्जा करने के लिए अनौपचारिक घरों को नियमित रूप से तोड़ा जाता है।
   - हालांकि, कौन (विशेष रूप से सरकार का कौन सा निकाय) भूमि का 'स्वामित्व' रखता है, इस बारे में जानकारी प्राप्त करना आसान नहीं है। यह महत्वपूर्ण जानकारी है क्योंकि पुनर्वास और मुआवज़े की गुंजाइश इस बात पर निर्भर करती है कि आप किस ज़मीन पर हैं। उदाहरण के लिए, यदि यह राज्य सरकार की भूमि पर है, तो उस पर रहने वाले लोगों को अधिक सुरक्षा प्राप्त होती है। हालांकि, अगर यह वन या रेलवे विभाग की जमीन पर है, तो कोई मुआवजा नहीं है। इसी तरह, पानी या बिजली जैसी बुनियादी सेवाओं के लिए आवेदन करते समय भूमि के स्वामित्व को जानना आवश्यक है। अनौपचारिक बंदोबस्त के कब्जे वाली जमीन का मालिक कौन है, यह जानना वहां रहने वाले लोगों और इस पर काम करने वाले कार्यकर्ताओं के लिए उपयोगी जानकारी होगी।
   - नक्शा शहर में भूमि 'कब्जे' (विशेष रूप से जिसे सरकार अवैध अनौपचारिक आवास के रूप में मानती है) और 'स्वामित्व' को एक दूसरे पर आरोपित करके शहर में संसाधनों के वितरण की कल्पना और खुलासा करता है।
   - यह नक्शा सरकार की झुग्गी की मैपिंग में त्रुटियों को देखने में भी मदद करता है। सरकार द्वारा खींची गई मलिन बस्तियों की सीमाएं अक्सर वास्तविकता से भिन्न होती हैं क्योंकि सरकार इस पर कब्जा करने में विफल रहती है। अनौपचारिक बस्तियों में रहने वाले लोगों के पास जमीन पर कम दावा होता है, जब वे आधिकारिक डेटासेट में 'अनगिनत' और 'अदृश्य' होते हैं। इस नक्शे के माध्यम से सरकारी नक्शों को सही करने के लिए अधिकारियों के पास विसंगतियां ढूंढी और उठाई जा सकती हैं (हालांकि तारीख का मुद्दा है।
   - यह नक्शा उन शिक्षाविदों के लिए भी उपयोगी है जो इस डेटा को समझना चाहते हैं

विशेषताएं
- भाषाओं के बीच टॉगल करना (हिंदी, मराठी और अंग्रेजी)
- स्थानीय खोज (खोज बार का उपयोग करके खोज बस्तियां)

## डेटा स्रोत और कार्यप्रणाली

1. भूमि का स्वामित्व- ग्रेटर मुंबई नगर निगम का डेटा, अक्टूबर 2020 तक का डेटा।
2. अनौपचारिक बंदोबस्त क्लस्टर- 2016 में स्लम पुनर्वास प्राधिकरण द्वारा बनाया गया नक्शा
3. पत्रक से सैटेलाइट मानचित्र टाइलें

## प्रौद्योगिकी ढेर

- डेटा सफाई और प्रसंस्करण के लिए आर, क्यूजीआईएस और मैप शेपर
- डेटा geoJSONs और TopoJSONs- डेटा स्टोरेज के रूप में संग्रहीत
- जेएस पुस्तकालयों जैसे पत्रक, पापा पार्स का उपयोग करके नक्शा बनाने के लिए जेएस
- एचटीएमएल, सीएसएस
- उपग्रह छवियों के लिए पत्रक आधार टाइलें।
- होस्टिंग के लिए जीथब पेज

--------

# जमीन मालक आणि रहिवासी: मुंबईतील वादग्रस्त जागा

## परिचय
मुंबईतील 52% लोक अनौपचारिक वस्त्यांमध्ये (किंवा झोपडपट्ट्यांमध्ये) राहतात (जनगणना 2011). मात्र, जमीन कोणाच्या मालकीची आहे आणि मालमत्तेच्या नोंदी काय दाखवतात याची माहिती मिळवणे सोपे नाही. हा नकाशा सेटलमेंट गट आणि त्यांच्या मालकीची माहिती दृश्यमान करतो.

## मॅपिंग उद्दिष्टे

- काय: जमिनीची मालकी आणि व्यवसाय
- कुठे: मुंबई, भारत
- केव्हा: माझ्याकडे 2016 आणि 2020 साठी सरकारी स्त्रोतांकडून डेटा आहे (आणि 2000 आणि 2012 साठी काही डेटा)
- का:
    शहराच्या अर्ध्याहून अधिक लोक अनौपचारिक वसाहतींमध्ये राहतात ज्यांना परवडत नसलेल्या औपचारिक गृहनिर्माण क्षेत्रातून बाहेर पडलेल्या लोकांच्या मालकीच्या जमिनीवर (बहुतेक) सरकारी (परंतु विविध स्तरांवर आणि संस्था) किंवा खाजगी बांधकाम व्यावसायिकांनी बांधले आहे. अनौपचारिक घरे शहराचे सुशोभीकरण करण्यासाठी आणि जमिनी बळकावण्यासाठी नियमितपणे तोडल्या जातात.
    - तथापि, जमिनीची मालकी कोणाची (विशेषत: सरकारची कोणती संस्था) 'मालक' आहे याची माहिती मिळवणे सोपे नाही. ही महत्त्वाची माहिती आहे कारण पुनर्वसन आणि भरपाईची व्याप्ती तुम्ही ज्या जमिनीवर आहात त्यावर अवलंबून आहे. उदाहरणार्थ, जर ते राज्य सरकारी जमिनीवर असेल तर त्यावर राहणाऱ्या लोकांना अधिक संरक्षण मिळते. मात्र, ती वन किंवा रेल्वे विभागाच्या जमिनीवर असेल, तर मोबदला मिळत नाही. त्याचप्रमाणे पाणी किंवा वीज या मूलभूत सेवांसाठी अर्ज करताना जमिनीची मालकी जाणून घेणे आवश्यक आहे. अनौपचारिक सेटलमेंटने व्यापलेली जमीन कोणाच्या मालकीची आहे हे जाणून घेणे तेथे राहणारे लोक आणि त्यावर काम करणाऱ्या कामगारांसाठी उपयुक्त माहिती असेल.
    नकाशा शहरातील संसाधनांच्या वितरणाची कल्पना करतो आणि शहरातील जमीन 'व्यवसाय' (विशेषत: सरकारला बेकायदेशीर अनौपचारिक घरे म्हणून काय समजते) आणि 'मालकी' वर छापून येते.
    या नकाशामुळे सरकारच्या झोपडपट्टी मॅपिंगमधील त्रुटीही पाहण्यास मदत होते. सरकारने आखलेल्या झोपडपट्ट्यांच्या सीमा अनेकदा वास्तवापेक्षा वेगळ्या असतात कारण सरकार त्या पकडण्यात अपयशी ठरते. अनौपचारिक वसाहतींमध्ये राहणारे लोक अधिकृत डेटासेटमध्ये 'अगणित' आणि 'अदृश्य' असताना जमिनीवर कमी दावा करतात. या नकाशाच्या माध्यमातून अधिकृत नकाशे दुरुस्त करण्यासाठी अधिकार्‍यांकडे विसंगती शोधून काढता येतात (जरी तारखेची समस्या आहे.
    - ज्यांना हा डेटा समजून घ्यायचा आहे त्यांच्यासाठीही हा नकाशा उपयुक्त आहे

गुणधर्म
- भाषांमध्ये टॉगल करा (हिंदी, मराठी आणि इंग्रजी)
- स्थानिक शोध (शोध बार वापरून सेटलमेंट शोधा)

## डेटा स्रोत आणि पद्धत

1. जमीन मालकी - बृहन्मुंबई महानगरपालिकेचा डेटा, ऑक्टोबर 2020 पर्यंतचा डेटा.
2. अनौपचारिक सेटलमेंट क्लस्टर्स - 2016 मध्ये झोपडपट्टी पुनर्वसन प्राधिकरणाने तयार केलेला नकाशा
3. पत्रकावरील उपग्रह नकाशा टाइल

## तंत्रज्ञान स्टॅक

- डेटा क्लीनिंग आणि प्रोसेसिंगसाठी आर, क्यूजीआयएस आणि मॅप शेपर
- geoJSONs आणि TopoJSONs म्हणून संग्रहित केलेला डेटा - डेटा स्टोरेज
- लीफलेट, पापा पार्स यांसारख्या JS लायब्ररीचा वापर करून नकाशा तयार करण्यासाठी JS
- html css
- उपग्रह प्रतिमांसाठी शीट बेस टाइल.
- होस्टिंगसाठी गिथब पृष्ठ
