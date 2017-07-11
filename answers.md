1#
 var img = document.querySelector("left-image")
 img.firstElementChild.src = "https://s-media-cache-ak0.pinimg.com/originals/2b/05/14/2b05140a776f25a8047c88fbe2bcbdb9.jpg"

 2#
var h1 = document.querySelector("h1")h1.innerText = "Manny the Bear"

3#

var h3 = document.querySelector("#employment .info-title")
h3.innerText = "unemployment"

4#  

var color = document.querySelector("body .highlight")
color.style.background = "black"

5#

var color = document.querySelector("body")
color.style.background = "black"  

6#

var font = document.querySelector("h1")
font.style.fontFamily = "monospace"
"monospace"

7#

var circle = document.querySelectorAll("aside a")
circle.forEach(function(icon) {icon.style.backgroundColor = "black"})

 8#
 var name = document.querySelector('input[name="name"]') name.placeholder = "Who are you"

 9#

 var message = document.querySelector('textarea[name="message"]')
 message.placeholder = " Money "

 10#

 nameField.value = "erjrj e"

 11#

 var email = document.querySelector('input[name="email"]') email.value = "koalathebear@gmail.com"


 12#

  var submit = document.querySelector('input[type="submit"]') submit.value = "En Garde lol!"

  13#

  submit.disabled = true

  14#

   var profileInfo = document.querySelectorAll('.bio-info-value') profileInfo.forEach(field) {field.innerText = ""})

   Part 2

   1#

   var remove = document.querySelector("#time-travel")
   remove.parentElement.remove()

   2#

   var portfolio = document.querySelector(".portfolio-container")
   var pikachu = document.querySelector("#right-image")
   portfolio.appendChild(pikachu.cloneNode())

   3#


    for (var i = 10; i > 0; i--) {
        portfolio.appendChild(pikachu.cloneNode())
    };

  4#

  var listItem = document.createElement("li");
  var leftSpan = document.createElement('span');
  var lastUpdated = document.createTextNode('Page last updated on');
  leftSpan.appendChild(lastUpdated);
  listItem.appendChild(leftSpan)
