## Obtaining a Google Maps API key

An API (or Application Programming Interface) is a set of functions provided so that you can interact with another computer - in this case the Google Maps server. You need to have an **API key** to access it, so that Google knows who it has allowed to use its services.

- You will need to [create a Google account](https://accounts.google.com/SignUp?hl=en) or use an existing Google account to be able to obtain an API key. There is a minimum age requirement to create an account which varies depending on which country you live in - please check [this page](https://support.google.com/accounts/answer/1350409?hl=en) first to see whether you are old enough to create an account.

- Open [this page](https://developers.google.com/maps/documentation/javascript/adding-a-google-map#step_3_get_an_api_key) and, under the heading “Step 3: Get an API key”, follow steps 1-4 to obtain a Google Maps JavaScript API key.

- To use your API key in a HTML page, open the file and position your cursor just before the `</body>` tag. Paste in the code below:

```html
  <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
  </script>
```
- Locate the part in the code you just pasted which says YOUR_API_KEY and replace it with the API key you just generated, making sure there are no spaces between the key you paste in and the = and & characters on each side of it.
