# HomeBuyerDiscounts Merchant Badge

## What is the purpose badge?

The HomeBuyer Discounts Merchant Badge is for our merchants to proudly display their membership in our network. Displaying this badge on your website links your traffic to https://www.homebuyerdiscounts.com which provides your customers access to the wonderful savings HomeBuyer Discounts provides.

## What will this badge look like on my site?

The HomeBuyer Discounts Merchant Badge will appear on your site as it does in the following screenshot.

![HomeBuyer Discounts Screenshot](https://raw.githubusercontent.com/gibbyxdesign/HomeBuyerDiscounts/master/example-screenshot.jpg)

## How do I add this to my website?

Adding this to your site is very easy. Simply copy and paste the following code to your website just above the closing *body* tag.

```html
<style>
	@import url(http://fonts.googleapis.com/css?family=Roboto:900);
	#hbd-badge{
	    display: block;
	    width: 253px; 
	    height: 99px; 
		border: 2px solid #12AE99; 
		-webkit-border-radius: 15px 15px 15px 15px;
		border-radius: 15px 15px 15px 15px;
		padding: 8px;
		position: fixed;
		top: 30px;
		right: -90px;
		text-decoration: none;
		text-align: center;
		-webkit-transition: all .5s ease;
		-moz-transition: all .5s ease;
		-ms-transition: all .5s ease;
		-o-transition: all .5s ease;
		transition: all .5s ease;
		z-index: 1000;
		background: white;
	}
	#hbd-badge:hover{
	    right: 5px;
	}
	#hbd-logo{
	    display: inline-block;
	    border-right: 2px;
	    padding-right: 10px;
	    border-right: 2px solid #12AE99;
	}
	#hbd-logo img{ width: 128px; }
	#hbd-text{
		display: inline-block; 
		font-family: 'Roboto', sans-serif;
		text-transform: uppercase;
		letter-spacing: .25em;
		font-size: 8px;
		color: #042745;
		float: right;
	}
	#hbd-text h2{ display: inline-block; margin: 0; width: 77px; }
</style>

<a href="https://www.homebuyerdiscounts.com" id="hbd-badge">
	<div id="hbd-logo">
		<img src="https://s3.amazonaws.com/xdesign.1/logo/logo.png" alt="HomeBuyer Discounts">
	</div>
	<div id="hbd-text">
		<h2>Certified Merchant</h2>
	</div>
</a>
```

Also supplied in this repository is an HTML file that you or your developer can use as a php include, asp inc, or any other framework you or your developer may be using.

## Tech Support

If you have issues implementing this badge into your website, please contact HomeBuyer Discounts at https://www.homebuyerdiscounts.com or email us at [info@homebuyerdiscounts.com](mailto:info@homebuyerdiscounts.com) .