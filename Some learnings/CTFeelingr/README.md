# <font color="blue">▄■▀■▄■▀■▄■▀■▄ [CTFeelings](https://cybersecuritybase.github.io/ctf/) ▀■▄■▀■▄■▀■▄■▀</font>
- - - -
🏠 **førstedag**|Pretty interesting tasks. But some of them with unclear reasoned view. |
----------------|-----------------------------------------------------------------------|

My own large stack was with "Key Validation Service Two". In general, based on my too small experience with JavaScript, Webpack and debugging such things.
It was clear where is 'flag'. But it was unclear how to 'calculate' (receive, find, decrypt, capture) it. And what if there are any other connections with something more than JavaScript. 

Also, Internet Explorer 11 (Windows 10) is not supported. Microsoft Edge was with not enough view under browser's console (I downloaded important .js-file manually). First try with expected place and another browser was with unexpected result. Just because it was not enough clear for me that indeed I have to think about it directly (and not about something else like studying webpack, chunks, other places or tricks) - I switched to another fields. After six hours - I back to expected place and start to try understand what is it (manually). So, even if it was possible to use browser's console for kind of 'compute' it. I did manual steps for recovering flag. Take quite count of time. Then double check that it was possible to calculate briefly and I found that my first try was with 'unintended' payload (and, as result, broken output).
All other tasks are pretty common and interesting ones. At least, for logical sorting. Exception with RSA calculation - based on something first tries to calculate was with huge delay about proper result. Decided to find good enough tool for such calculation. And result is received briefly (as expected for such task).

🌲 **andendag**|Much more strange reasoned tasks, but with interesting scale. |
---------------|--------------------------------------------------------------|

In general, tasks with large scale of its design. While most of them was sorted pretty briefly - my own experience was with three stucks.
Where two stucks was with unclear 'expected' flag-view state. I tried multiple valid steps - but switch to find something else or re-tweak solution. It take some unwanted hours (as result). And third stuck is still delayed; it is third "Key validation service". Task with clear design and what we are supposed to do. Also, with potentially visible steps to do so - but based on my too small experience with JavaScript, browser's console debugging and things around (not really enjoy to play with it) - I switched from this task to next day (because one of previously noted stucks was with enough delay for situation that there are released already and, as result, locked third day; so, with sort-step for 'second' stuck - I switch to next available tasks).

Also, I am not sure about such JavaScript(?) tasks. It is not pinned to course itself. And maybe it is interesting one but too much specific. For example, "hemmeligmalingr" tasks are tricky too (of course) - but with certain tools - less time needed. Even my noted 'second' stuck was about manual extracting and playing with such for doublecheck (while with tools - it should take some minutes only).
With JavaScript tasks - I am not so friendly with most of 'related' fields. Just like if someone else with [Fjölnir](https://is.wikipedia.org/wiki/Fj%C3%B6lnir_(forritunarm%C3%A1l)). But maybe debug/learn task about 'something' written on Fjölnir is more interesting than "Key Validation Services Three/Four" (and even "Two").

🚉 **tredjedag**|In general, sorted speedy than two others. |
----------------|-------------------------------|

After sorting latest task for unlock fresh tasks - all of them was released already. So, less then thirty minutes and there are only "Key Validation Service Four" and "secret_c" are unsorted. First one is postponed for futher play with it (as previous Key Validation Service too). And with "secret_c" - I tried to check and play statically. With some potential steps and checking information.
Even if it with some results - based on my too much small experience (too much) with kind of executables-debug and Linux - I delayed further play for installing Linux 64bit and potential debug it directly (dynamically). Or so on.

    ╒═════════════╕
    ╏later eddited╏
    ╚━━━━━━━━━━━━━╝

↪ after two-days delay - I back to unsorted three tasks ("secret_c" and Key Validation Service III/IV).
I decided to continue with 'static'-analysis and potential tries to use software like Snowman ('disassembler') as decompiler tool under Windows. It was with good enough result (in general, based on 'basic' task and design of secret_c). But based on my too much small experience with any of such things (like disassemblers, decompilers, debugging and Linux software) - I was confused about. And decided to install Debian 64bit. Then to try debug/play with gdb and some other tools. It was interesting experience, but not real part of my further sort steps. Play with "secret_c" was about six or eight hours (include some delays) where most time was about research and learn things about potential debugging, asm and so on.

Based on basic design of secret_c - my feelings was always about too generic solution. I thought about different potential tricks (include tricky task like disasm/decompile -> modify if|else-> recompile back ....) and most of them was about 'need to know how to perform such step'. So, I decided to think more about potential 'jump' to success-point. During my tries to re-check situation with potential proper breakpoints and potential jumps... I decided to re-check my 'first' thought (which was after too visible 'characters' of flag - and what I tried and where it was not enough and I switched to other tries around). I decided to re-look more about "what is movsx" (which I ignored firstly) - because instructions start be more clear (after all noted experience). And, yes, it was perfect!
So, with proper experience - such task (well-designed for this basic course) should be sorted pretty briefly (maybe fifteen minutes or less). But I am not sure that my own sort-design is expected sort steps (since access to direct flag - rather than to potential password - if it was expected).

As result, only "Key Validation Service III and IV" are unsorted. In fact, I did not look for them yet (practically at all).
Not sure if such tasks are well-fitted to this course. Probably it is interesting design for JavaScript lovers (and debuggings things around) and probably it is pretty basic ones. But I am not like JavaScript (and things around are not really interesting for me).
But I feel that design and expected steps to sort it - pretty cool an good enough!
But for sort such tasks - I have to learn more about "how to work with JavaScript and advanced browser's console" (if such steps are needed). For example, even second Key Validation Service was a basic one - but it was unclear for me how to re-use browser's console with enough result. So, I did manual compute calculation and research about some technologies. Then only re-check that it was pretty brief task with browser's console itself....

So, will play with "Key Validation Service III/IV" later.

- - - -

Today I tried to play with "Key Validations Service III and IV" a little be. In general, maybe some hours (two or four).
Still I'm not sure about such task with this course. Design of task is probably good and interesting - but I think that too much pinned to certain 'tool' (like JavaScript or even browser's abilities) rather than to technologies or so. I'm not sure that there are pretty large count of workarounds - but I tried multiple ones. Then switch to static analysis each string of .js-files and potential 'important' lines. With both of "KVS" - maybe I found and (play with) potential strings-to-be-flag (or good advice) - but ?! with tries to re-use browser's console (or so) with not much result (as it was with KVSII too). So, I tried to do it manually - but it will take already much more time... so I decided to delay it. Will re-try later. Pretty likely that with browser's console or other tools (with enough understanding only '.js'-wording) -> sort such task is not tricky; but probably 'general understanding' of potential sort steps are not enough). And, as result, out-of-course design. Even GSM/GPRS was discussed more time. Where design of potential task is more valuable rather than 'debug' tricks with .js (or certain libraries).
