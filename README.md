# How to unsubscribe from all the Youtube channels at once?
### Just follow these simple steps 💡

 1. Go to [Youtube Subcription Manager](https://www.youtube.com/subscription_manager)
 2. Press F12 or ctrl + shift + I.
 3. Copy the code.
```javascript
$$(".yt-uix-button-subscribed-branded").forEach(function (el) {
  el.click();
  $$(".overlay-confirmation-unsubscribe-button").forEach(function (el) {
    el.click();
  });
  console.log("Unsubcribe");
});

````
 4. Clear your console.
 5. Paste it & see the magic.

### How it works ? 🧓

![10fps](https://user-images.githubusercontent.com/37630292/94128230-b20f4880-fe7b-11ea-8c0d-29c6cbdfff25.gif)
