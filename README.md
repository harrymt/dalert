DAlert 1.1.0
======

Dalert is a simple jQuery and jQuery UI plugin that easily create a customizable alert (or confirm) window as a replacement for the native javascript alert and confirm methods.
Dependencies : jQuery, jQuery UI



* Homepage & Documentation: [http://andrewdex.github.io/dalert]


## Simple usage

//Dalert Alert Dialog
```js
dalert.alert("I am a liitle DAlert !"); 
```
//Dalert With Callback
```js
//Start :: DAlert Alert Usage with a callback on close of the alert		
    dalert.alert("Hello, I am a DAlert!","Title", function callbackMe(){
        dalert.alert("Me callback !");
    });
//End :: DAlert Alert Callback Usage
```

//Dalert Confirm Dialog
```js
dalert.alert("Are you sure ? ", "Confirm Tittle" , 
function(result){
	if(result){
	//If yes clicked 
	dalert.alert("Clicked yes"); 
	}
	else{
	//if no clicked
	dalert.alert("Clicked no"); 
	}
}
);
```


## Getting started
Download the [latest release](https://github.com/andrewdex/dalert/archive/master.zip) or clone the repo, `git clone git://github.com/andrewdex/dalert.git`.

