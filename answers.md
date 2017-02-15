1 $('img.profile-image').attr('src','http://elrincondelgeek.files.wordpress.com/2011/04/google-chrome-logo-400x400.jpg')

2 $('h1').text('Joel The Angry Bear')

3 $('#employment .info-title').text('History')

4 $('#time-travel').remove()

5 $('body').css('background-color','red')

6 $('.highlight').css('color', 'yellow')

7 $('h1').css('font-family', 'monospace')

8 $('.action-icon-bg').css('background-color', 'white')

9 $('.contact-info#name').attr('placeholder', 'idintify yourself')

10 $('#message').attr('placeholder', 'state your business')

11 $('.contact-info#name').attr('value', 'Your Nemesis')

12  "koalathebear@gmail.com"

13 $('#submit').attr('value', "En garde!")

Adding Elements to the DOM

1 $('#right-image').clone().insertAfter('form')

2 for (i = 0; i < 10; i++) { $('#right-image img').clone().appendTo('form'); }

3
var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);
