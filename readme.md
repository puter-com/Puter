Computers. Abbreviated.

## Questions and Answers 

<details><summary>What is an API?</summary>

### What is an API 
```
An API is a useful way for computer programs to ask things from other computer programs.
```

> Let's say you call a pizzeria to order a margheritta. The service that consists of "a number" where you "place your order" and that results in a "it'll be there in 45 min" is your pizza "API". Because its a human conversation, the request can be different if 2 different people call, but it will always have to involve the same convention: the pizzeria staff needs to know your name, address, pizza preference, and with they'll be able to tell you an estimated delivery time.

> After selling 10'000 pizzas, the pizzeria gets tired of phone calls. They tell you to just call https://www.thepizzeria.com/your-name/your-full-address/the-pizza-you-want-and-quantity/ and that's it. They will extract your details from that url you enter in your browser and show you on the page whether they can deliver it or not. What they created is an API!

### What makes an API

* An API offers a method for a particular program to do a request to another program. Its a convention of how the program can talk to the other program.
* You can say an API is made of 2 events: the `request` and the `response` to the request.
    * the `request` involves:
        * a particular `target` (which is formally called an `endpoint` in web APIs): where are you placing the request or who are requesting this from. It can be a web address (an URL). The `target` or `endpoint` is the entity responsible for processing the `request`, doing anything that's asked, and then responding.
        * the `content` of your message: this is a particular `schema` (a layout of the information), the actual `data` and a `format`.
    * the `response` involves the `content` too.

### Common Types of APIs

* Web APIs. These are the APIs that let your web-platform or application access the functionality of provided by a another computer program accross the internet. The payment APIs of Paypal are Web APIs.
* Operative System APIs: operative systems like Windows and iOS provide APIs that let application creators execute common functions easily. Send alerts to the user, get a web page to display inside your application or doing complex mathematical computations - all of those things can be provided by Operative Systems APIs.

### Examples of APIs
* When you login in into your online bank account, the bank website logs you in by asking a central bank API to check if the username and password you provided are ok. The API returns something like "OK" or "Not OK", and it frequently also returns some basic info on your account11.
* When you tell your bank app to transfer money to a friend, the banks app is sending an API request to the Bank server telling it that you want to move money to your friend's bank account. The bank will, then, send a separate API request to your friends bank (or a central authority) telling them that you moved money to your friends account. The APIs will respond with the status of those operations and potentially more detail.
* When you play a 3D game in your Phone, the game app will like be calling a system API to access the 3D potential of the graphics processor of the phone. On  
* Definition: `API` means `Application Programming Interface`. An API is an interface between two software programs which facilitates interactions between them.

</details>


### What is a Software Library?



### What is a Framework?



### What is an SDK?

### What is the difference between an SDK, a Framework, an API and a software library?