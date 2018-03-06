# <font color="blue">▄■▀■▄■▀■▄■▀■▄ [CTFeelings](https://cybersecuritybase.github.io/ctf/) ▀■▄■▀■▄■▀■▄■▀</font>
- - - -
🏠 **førstedag**|Pretty interesting tasks. But some of them with unclear reasoned view. |
----------------|-----------------------------------------------------------------------|

My own large stack was with "Key Validation Service Two". In general, based on my too small experience with JavaScript, Webpack and debugging such things.
It was clear where is 'flag'. But it was unclear how to 'calculate' (receive, find, decrypt, capture) it. And what if there are any other connections with something more than JavaScript. 

Also, Internet Explorer 11 (Windows 10) is not supported. Microsoft Edge was with not enough view under browser's console (I downloaded important .js-file manually). First try with expected place and another browser was with unexpected result. Just because it was not enough clear for me that indeed I have to think about it directly (and not about something else like studying webpack, chunks, other places or tricks) - I switched to another fields. After six hours - I back to expected place and start to try understand what is it (manually). So, even if it was possible to use browser's console for kind of 'compute' it. I did manual steps for recovering flag. Take quite count of time. Then double check that it was possible to calculate briefly and I found that my first try was with 'unintended' payload (and, as result, broken output).
All other tasks are pretty common and interesting ones. At least, for logical sorting. Exception with RSA calculation - based on something first tries to calculate was with huge delay about proper result. Decided to find good enough tool for such calculation. And result is received briefly (as expected for such task).
