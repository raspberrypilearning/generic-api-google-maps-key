## Google maps API key प्राप्त करना

एक API (या Application Programming Interface) फंक्शन्स​ का एक सेट है जो आपको किसी अन्य कंप्यूटर के साथ बातचीत करने की अनुमति देता है—इस मामले में Google Maps सर्वर। इसे एक्सेस करने के लिए आपके पास **API key** होना आवश्यक है, ताकि Google को पता हो कि उसने अपनी सेवाओं का उपयोग करने की अनुमति किसको दी है।

- आपको [Google खाता बनाने की](https://accounts.google.com/SignUp?hl=en) आवश्यकता होगी, या किसी मौजूदा Google खाते का उपयोग करें, API key प्राप्त करने के लिए। एक खाता बनाने के लिए न्यूनतम आयु की आवश्यकता है जो देश-देश में भिन्न होती है—कृपया [इस पृष्ठ](https://support.google.com/accounts/answer/1350409?hl=en) को देखें यह देखने के लिए कि क्या आपकी आयु उपयुक्त है।

- [इस पृष्ठ](https://developers.google.com/maps/documentation/javascript/adding-a-google-map#step_3_get_an_api_key) को खोलें और, शीर्षक के तहत "चरण 3: एक API key प्राप्त करें", Google Maps JavaScript API Key प्राप्त करने के लिए चरणों का पालन करें।

  **नोट - API का उपयोग करना नि: शुल्क है लेकिन साइन अप को पूरा करने के लिए आपको क्रेडिट/डेबिट कार्ड की आवश्यकता होगी।**

- HTML पेज में अपनी API key का उपयोग करने के लिए, HTML फ़ाइल खोलें और `</body>` टैग को खोजें। इस टैग के ऊपर निम्न कोड पेस्ट करें।

```html
  <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
  </script>
```
- आपने जिस कोड को पेस्ट किया हैं उसमें वह भाग ढूंढें जो कहता है `Your_API_KEY`, और इसे आपके द्वारा उत्पन्न API key से बदल दें। सुनिश्चित करें कि आपके द्वारा पेस्ट की गई key के बीच और इसके दोनो तरफ के अक्षर `=` और `&` के बीच कोई रिक्त स्थान नहीं है।
