# How to unsubscribe from all the Youtube channels at once?
### Just follow these simple steps 💡

 1. Go to [Youtube Subcription Manager](https://www.youtube.com/subscription_manager) here
 2. Press F12 or ctrl + shift + I
 3. Copy the code
```javascript
$$(".yt-uix-button-subscribed-branded").forEach(function (el) {
  el.click();
  $$(".overlay-confirmation-unsubscribe-button").forEach(function (el) {
    el.click();
  });
  console.log("Unsubcribe");
});

````
 4. Clear your console .
 5. Paste it & see the magic


### Build your youtube channel fresh.
