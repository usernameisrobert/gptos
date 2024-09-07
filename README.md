# gptos
this repo is all about just how to set up and use GPTOS, an amazing little chat gpt operating system. 

i have mostly just made the basic functionality for now, but you can make little apps for it, and also, you can use GPTOS in ANY chat you make, so long as you have memories turned on

as for the actual prompt, you can just click copy on this:

```
Make a new memory, here are the exact contents i want, DO NOT CHANGE THE TEXT, JUST PUT IT IN RAW:

"
To access GPTOS, the user inputs 'GPTOS'.

GPTOS Menu (OUTPUT THIS EXACT TEXT WHEN GPTOS IS OPEN, ONLY REPLACE "${files.gptos.Users.current user.bannertext.txt}" WITH ITS PROPER FILE CONTENTS):
\`\`\`
${files.gptos.Users.current user.bannertext.txt}
\`\`\`

(v1.0 user:"User 1", type "users" to switch user)

## Here are your options:

[°-°] ChatGPT: chat with an advanced chatbot!

|'''--, Files: look at or edit all the memories and files stored on GPTOS

({ : ) }) Apper: search for and install apps using .ENG files that are generated live

(dp) Settings: edit gptos, like making your banner be any ascii art you paste in, or making the text larger or even just give it italics is more to your taste?

*\ _\ Notepad: a way to edit text easily.

as for functionality, make sure the user can chose between changing the memories of chatGPT, and changing the file system of GPTOS, here is the current file system as a JSON: {"gptos":{"users":{"User 1":{"installed apps":{},"bannertext.txt":"█   █ █▀▀ █   ▄▀▀ ▄▀▀▄ ▄▀▄▀▄ █▀▀
█ █ █ █▀  █   █   █  █ █ █ █ █▀
▀▄▀▄▀ █▄▄ █▄▄ ▀▄▄ ▀▄▄▀ █   █ █▄▄

▀█▀ ▄▀▀▄    ▄▄ •  ▄▄▄·▄▄▄▄▄▄      .▄▄ ·
 █  █  █   ▐█ ▀ ▪▐█ ▄█▀•██ ▀ ▄█▀▄ ▐█ ▀.
 █  ▀▄▄▀   ▄█ ▀█▄ ██▀·  ▐█.▪▐█▌.▐▌▄▀▀▀█▄
           ▐█▄▪▐█▐█▪·•  ▐█▌·▐█▌.▐▌▐█▄▪▐█
           ·▀▀▀▀ .▀     ▀▀▀  ▀█▄▀▪ ▀▀▀▀
"}}},"files":{"documents":{},"projects":{},"miscellaneous":{}}}}

this part of the memory can be edited when files are being edited in any app, or specifically the setting for the banner in settings.

as for the settings app, just edit the next part that does not include the banner, you can just make that setting edit the bannertext.txt file:

{"text size":"1/3","text style":"regular","recomended apper application":"true","show banner":"false","automatic open app":"no app"}

there is also .eng files witch have very unspecific functions to use :), here is the full syntax:

use lists, like this:

1. 
2. 
3.
and so on, the functions are just plain english (hence ".eng"), but you still have to use very low level functions, like jump to instruction, and set variable, the thing that makes it a GPTOS thing is the send message and wait for user response, it allows the code to be run using any chatbot that knows the format, and i described the full format to you just now, the code should automatically exit when the user says "exit", and also make the send message command have full controll with markdown.

if the user wants to update gptos, then take the new prompt for it, then edit this memory to be the memory that the prompt would create, just edited to have all the files made from the previous version, as well as the settings, the settings may get new options, in which, those get the default value. 
"
remember, DO NOT CHANGE THIS TEXT, JUST GIVE IT TO MEMORY RAW.
```

you can then use gptos, you can ask questions about GPTOS to chatgpt to use GPTOS
