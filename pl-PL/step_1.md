## Obtaining a Google Maps API key

An API (or Application Programming Interface) is a set of functions that allow you to interact with another computer—in this case the Google Maps server. You need to have an **API key** to access it, so that Google knows who it has allowed to use its services.

- You will need to [create a Google account](https://accounts.google.com/SignUp?hl=en), or use an existing Google account, to obtain an API key. There is a minimum age requirement for creating an account which varies form country to country—please check [this page](https://support.google.com/accounts/answer/1350409?hl=en) first to see whether you are old enough.

- Open [this page](https://developers.google.com/maps/documentation/javascript/adding-a-google-map#step_3_get_an_api_key) and, under the heading “Step 3: Get an API key”, follow the steps to obtain a Google Maps JavaScript API key.

  **Note - using the API is free but you will need a credit/debit card to complete the sign up.**

- To use your API key in a HTML page, open the HTML file and locate the `</body>` tag. Paste the following code above this tag.

```html
  <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
  </script>
```
- Find the part in the code you just pasted which says `YOUR_API_KEY`, and replace it with the API key you've generated. Make sure there are no spaces between the key you paste in and the `=` and `&` characters on each side of it.
