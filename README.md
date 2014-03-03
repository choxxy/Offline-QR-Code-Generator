Copy text/URL from your laptop to your mobile phone.
Type long text messages to on your laptop and simply transfer them to your mobile with one scan!
 
Offline QR-Code Generator lets you generate QR codes locally without having you to be connected to the internet!

Use any 'QR Code' scanner on your iOS/Android device!

- Generate QR code instantly ! 
- No internet connectivity required
- Large size QR Code size (400x400)
- No server lag
- Quick and easy open/close pop-up extension

Its light, quick and handles all codes!

Generate QR codes for text, URLs, phone numbers, SMS messages, or contacts (vcard).


# QRCode.js
QRCode.js is javascript library for making QRCode. QRCode.js supports Cross-browser with HTML5 Canvas and table tag in DOM.
QRCode.js has no dependencies.

## Basic Usages
```
<div id="qrcode"></div>
<script type="text/javascript">
new QRCode(document.getElementById("qrcode"), "http://jindo.dev.naver.com/collie");
</script>
```

or with some options

```
var qrcode = new QRCode("test", {
	text: "http://jindo.dev.naver.com/collie",
	width: 128,
	height: 128,
	colorDark : "#000000",
	colorLight : "#ffffff",
	correctLevel : QRCode.CorrectLevel.H
});
```

and you can use some methods

```
qrcode.clear(); // clear the code.
qrcode.makeCode("http://naver.com"); // make another code.
```

## Browser Compatibility
IE6~10, Chrome, Firefox, Safari, Opera, Mobile Safari, Android, Windows Mobile, ETC.

## License
MIT License

## Contact
twitter @davidshimjs