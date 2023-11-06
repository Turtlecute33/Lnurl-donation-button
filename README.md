# CryptoDonate - Bitcoin and Lightning Donation Button

CryptoDonate is a JavaScript library that allows you to easily integrate Bitcoin and Lightning Network donation buttons into your website or web application. With CryptoDonate, you can provide your users with a convenient way to make donations using Bitcoin or Lightning.

## Features

- Integration of Bitcoin and Lightning Network donation buttons.
- Customizable appearance to fit your website's design.
- Lightning node not required.

## Usage

1. Include the CryptoDonate JavaScript file in your HTML:

```html
<script src="CryptoDonate.js"></script>


	<script>
		! function(c) {
			var t = document.createElement("script");
			t.type = "text/javascript", t.async = !0, t.onload = c, t.src = "CryptoDonateButton/src/widget.js";
			var e = document.getElementsByTagName("script")[0];
			e.parentNode.insertBefore(t, e)
		}(function() {
			Fr.loadCD("bitcoin", {
				coin: "bitcoin",
				address: "bc1qpcfagedq6tqf55lr0cqzlywsewq07p682r7p5a",
				buttonClass: "large",
				dialogClass: "large",
			});
		});
	</script>
```

Then just create an html tag in the same HTML page with the same #id choosed in the FrLoad variable. Example:
```html
"< span id="bitcoin"></ span>"
```

  ## Personalization
  You should edit these variables:
  
  - Fr.loadCD: set a name for call the library in Html
  - coin: "BITCOIN or LIGHTNING"
  - address: "YOUR BITCOIN ADDRESS / YOUR LNURL",
  - buttonClass: "SMALL / MEDIUM / LARGE",
  - dialogClass: "SMALL / MEDIU M/ LARGE",
        
     

	<Br><Br>
	
Now you have a beautiful Bitcoin donation button on your website!
	
	
  
 
