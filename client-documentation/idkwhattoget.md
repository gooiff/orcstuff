# full credit to idkwhattoget for this documentation.
# how to patch bobloxz april 2011 and beow working 2022 no scam no clickbait
(i will use a 2010 client for this)<br>
step 1: open the client in x32dbg<br>
![ntdll open in x32dbg](https://cdn.discordapp.com/attachments/958720769687425138/959178592263217183/unknown.png "ntdll")<br>
it should look like the thing above
<br>
<br>
<br>
now ntdll is open and not the client, so click on symbols (![a](https://cdn.discordapp.com/attachments/958720769687425138/959179153733718016/unknown.png)) and select your client<br>
![](https://cdn.discordapp.com/attachments/958720769687425138/959179505304502362/unknown.png)<br>
![](https://cdn.discordapp.com/attachments/958720769687425138/959179955755954267/unknown.png)<br>
now you are actually debugging the client<br>
![](https://cdn.discordapp.com/attachments/958720769687425138/959180101554151434/unknown.png)<br>
click on the little az button (![](https://cdn.discordapp.com/attachments/958720769687425138/959180397336473710/unknown.png)) at the top<br>
now wait for the green bars to load<br>
![](https://cdn.discordapp.com/attachments/958720769687425138/959180638966136842/unknown.png)<br>
now we can do some patching
# names
type "Set a Player's name" in the search bar ![](https://cdn.discordapp.com/attachments/958720769687425138/959180927915946004/unknown.png) at the botton<br>
double click on the top one ![](https://cdn.discordapp.com/attachments/958720769687425138/959181180043935744/unknown.png)<br>
select the push 3 or push 4 at the bottom (it depends on the client)
![](https://cdn.discordapp.com/attachments/958720769687425138/959181358712914051/unknown.png)<br>
press the spacebar<br>
this window should show up, change the push 0x3 or push 0x4 to push 0x0
![](https://cdn.discordapp.com/attachments/958720769687425138/959181999002759208/unknown.png)<br>
![](https://cdn.discordapp.com/attachments/958720769687425138/959182194037887006/unknown.png)<br>
then press ok<br>
after that, press ctrl + p then click patch file<br>
name the file what you want the client name to be<br>
like if i want the file to be named RobloxAppPatched.exe, i place in this:
![](https://cdn.discordapp.com/attachments/958720769687425138/959182589556555816/unknown.png)<br>
make sure to put the exe
# trustcheck
im so tired i will do this later

edit: i wont do the trustcheck cuz im lazy
