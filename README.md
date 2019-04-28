32b
===

This is a joke project by xem and bburky.

What if I told you that virtually every web app can fit in 32 bytes of code?

We dit it.

Here are the 32 bytes we're talking about:

    <body onload=eval("'"+location)>

Yep, all it does is evaluating the URL.

But what do you do in the URL?

This:

    http://xem.github.io/32b/#';INSERT_JAVASCRIPT_CODE_HERE;

or this:

    http://xem.github.io/32b/#';document.write('INSERT_HTML_CODE_HERE');

Here's a builder to help you in your 32b quest:

http://xem.github.io/32b/builder.html

And here is a demo:

<br>

<a href="http://xem.github.io/32b/#';document.write(unescape(atob('LiUzQ3NjcmlwdCUzRSUwQWV2YWwlMjh6JTNEJTI3cCUzRCUyMiUzQyUyMislMjJwcmUlM0UlMjIvKiUyMCUyQy5vcSUyMyslMjAlMjAlMjAlMjAlMjAlMkMuXyUyQyUyMCovJTNCZm9yJTI4eSUyMGluJTIwbiUzRCUyMnp3MjRsNmslNUMlMEE0ZTN0NGpudDRxajI0eGgyJTIweC8qJTIwJTNEJTNDJTJDbSUyM0YlNUUlMjAlMjAlMjAlMjBBJTIwVyUyMyUyMyUyM3EuJTIwKi80Mmt0eTI0d3J0NDEzbjI0M24lNUMlMEE5aDI0M3BkeHQ0MWNzYiUyMHl6LyolMjAlMjNLJTIwJTIwJTIwJTIwJTIwJTIwJTIwcSUyMyUyM0glMjMlMjMlMjMlMjMlMjMlMjNBbSUyMCovNDNpeWI2azQzcGs3MjQzbm0lNUMlMEFyMjQlMjIuc3BsaXQlMjg0JTI5JTI5JTdCLyolMjBkUCUyMCUyMCUyMCUyMCUyMCUyMGNwcSUyM3ElMjMlMjMlMjMlMjMlMjMlMjMlMjMlMjMlMjMlMjNiJTJDJTIwKi9mb3IlMjhhJTIwaW4lMjB0JTNEcGFycyU1QyUwQWVJbnQlMjhuJTVCeSU1RCUyQzM2JTI5Ky8qJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwcCUyMyUyM0AlMjMlMjMlMjNZRyUzRCU1QiUyMyUyMyUyMyUyMyUyMyUyMyUyM3klMjAqLyUyOGUlM0R4JTNEciUzRCU1QiU1RCUyOSUyOWZvciU1QyUwQSUyOHIlM0QlMjFyJTJDaSUzRDAlM0J0JTVCYS8qJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwZCUyM3FnJTIwJTYwKlBXbyUyMyUyM3ElMjMlMjMlMjMlMjMlMjMlMjMlMjNEJTIwKi8lNUQlM0VpJTNCaSslM0QuMDUlMjl3aSU1QyUwQXRoJTI4TWF0aCUyOXgtJTNEJTIwLyolMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjBhZW0xay5jb20lMjBRJTIzJTIzJTIzS1dSJTIzJTIzJTIzJTIzJTIwVyU1QiUyMCovLjA1JTJDMCUzQ2NvcyUyOG8lM0QlNUMlMEFuZXclMjBEYXRlLzFlMy8qJTIwJTIwJTIwJTIwJTIwJTIwLlElMjMlMjMlMjMlMjMlMjMlMjMlMjMlMjMlMjNNZCUyMy4lMjMlMjMlMjNPUCUyMCUyMEFAJTIwJTJDJTIwKi8teC9QSSUyOSUyNiUyNiUyOGUlNUIlN0UlNUMlMEElN0UlMjgzMipzaW4lMjhvJTI5Ki8qJTIwJTJDJTIwJTIwJTIwJTIwJTI4VyUyMyUyMyUyMyUyMyUyM1h4JTIzJTIzJTIzJTIzJTIzJTIzLlAlNUUlMjAlMjAlMjAlMjAlMjBUJTIwJTI1JTIwKi9zaW4lMjguNSt5LzclMjklMjklNUMlMEErNjAlNUQlMjAlM0QtJTdFJTIwciUyOSUzQi8qJTIwJTIzeSUyMCUyMCUyMCUyMCU2MCU1RVRxVyUyMyUyMyUyMyUyM1AlMjMlMjMlMjNCUCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCovZm9yJTI4eCUzRDAlM0IxMjIlM0UlNUMlMEF4JTNCJTI5cCslM0QlMjIlMjAlMjAlMjAqJTIzJTIyLyolMjBiLiUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyME9RJTIzJTIzJTIzJTIzeCUyM0slMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAqLyU1QmUlNUJ4KyslNUQrZSU1QngrKyU1QyUwQSU1RCU1RCU3QyU3QyUyOFMlM0QlMjglMjJldmFsJTIyLyolMjBsJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTYwWCUyMyUyMyUyMyUyMyUyM0QlMjAlMjAlMkMlMjAlMjAlMjAlMjAlMjAlMjAlMjAqLyslMjIlMjh6JTNEJTVDJTI3JTIyK3ouc3BsJTVDJTBBaXQlMjhCJTIwJTNEJTIwJTIyJTVDJTVDJTVDJTVDJTIyJTI5Li8qJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwRyUyMyUyMyUyMyUyM0IlMjIlMjAlMjMlMjAlMjAlMjAlMjAlMjAlMjAlMjAqL2pvaW4lMjhCK0IlMjkuc3BsaXQlNUMlMEElMjhRJTNEJTIyJTVDJTI3JTIyJTI5LmpvaW4lMjhCK1EvKiUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMFZRQlAlNjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAqLyUyOStRKyUyMiUyOS8vbTFrJTIyJTI5JTVCeC8yJTVDJTBBKzYxKnktMSU1RCUyOS5mb250Y29sb3IvKiUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMFRQJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwKi8lMjgvJTVDJTVDdy8udGVzdCUyOFMlMjklMjYlMjYlMjIlMjMlNUMlMEEwM0IlMjIlMjklM0Jkb2N1bWVudC5ib2R5LmlubmVySFRNTCUzRHArJTNEQislMjIlNUMlNUNuJTIyJTdEc2V0VGltZW91dCUyOHolMjklMjclMjkvLyUwQSUzQy9zY3JpcHQlM0U=')));location.hash=''">world1k by aemkei</a>

Tested & working on Chrome, IE11, opera, safari... and Firefox finally!
