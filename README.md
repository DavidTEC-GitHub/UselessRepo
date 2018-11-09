*   [Introduction](index.html#introduction)
*   [Contents](index.html#contents)
*   [Banning Players](index.html#banning-players)
*   [Ban Evasion](index.html#ban-evasion)
*   [Muting Players & Dealing with Spam](index.html#ban-evasion)
*   [Find Proof, Players and some General Commands](index.html#finding-proof-and-finding-players)

*   [Docs](index.html#document-index) »
*   DistrictMC Staff Documentation

* * *

# Welcome to DistrictMC’s staff documentation![¶](#welcome-to-documentation "Permalink to this headline")


## Introduction[¶](#a-simple-example "Permalink to this headline")

Welcome to the introduction of the documentation. This is the staff documentation for anyone who wants to either be staff or for the people who are staff.

This documentation should show you how to be a functioning staff member on the server.

## Contents[¶](#contents "Permalink to this headline")

### Banning Players[¶](#banning-players "Permalink to this headline")

Banning is pretty simple. Here is a step by step plan on how to do it.

First, obtain proof/evidence of the cheater. We recommend using [OBS](https://obsproject.com/) but you can use whatever you want.  
Once you have these you can ban the player like this. You need to replace [USER] with the username.  
```/tempban [USER] [LENGTH] [REASON] -s```
Here is a filled in example:
```/tempban JackCrispy 30d Kill Aura -s```
You may wander what is bannable. Here is a simple table of cheats.  

| Cheat/Offence                           | Ban Length (First Offence) | Ban Length (Second Offence) | Ban Length (Third Offence) | 
| ----------------------------------- | ------------------------------ | ---------------------------------- | ------------------------------- | 
| Kill-Aura                                    | 30 Days                              | 60 Days                                    | Permanent                           |  
| Anti Knockback                        | 30 Days                              | 60 Days                                    | Permanent                           |  
| Xray/ChestESP                         | 20 Days                              | 40 Days                                    | Permanent                           |  
| Auto-Soup                                | 15 Days                              | 30 Days                                    | Permanent                           |  
| Fly                                             | 15 Days                              | 30 Day                                     | Permanent                            |  
| Non-Malicious Cheats/Hacks  |  3 Days                                | -                                               | -                                            |  
| Mute Evasion                           |  3 Days                                | 15 Days                                   | -                                            |  

Any unlistead cheats/hacks/offences such as Derp will always be a 3 day ban as represented by the dashes (-) in the table as they would be part of the Non-Malicious Cheats/Hacks.  
### Ban Evasion[¶](#ban-evasion "Permalink to this headline")

Usually staff members will get messages in chat of that say who is ban evading that looks similar to this example:

![Ban Evasion Console Screenshot](_images/banevasion-screenshot-console-example.png)

Please note that staff will not be able to see players' IPs.  
If you want to manually check if a user is ban evading, you need to run the following command:  
```/dupeip [USER]```
If a player ban evaids they could be punished in multiple ways. Here is a table that shows how the cheaters woukd be banned.  

| Main Account Offence              | Consequence                                                     |  
| ----------------------------------- | ----------------------------------------------------- |  
| Malicious Cheats/Hacks           | Permanent Ban on All Accounts under their IP |  
| Non-Malicious Cheats/Hacks   | Same length ban on alt                                      |  
| Ban Evasion                              | Permanent Ban on All Accounts under their IP |  

### Muting Players & Dealing with Spam[¶](#settings "Permalink to this headline")

Muting players is very useful so you can stop people from spamming or advertising in the chat.  
You might wander how to mute players, well it is simple. Here is how:  

```/mute [USER] [LENGTH] [REASON] -s```

Here is a filled in example:  
```/mute JackCrispy 5m Spamming -s```

You may wonder what is mutable. Here is a list.  

| Offence                                     | Mute Length (First Offence) | Mute Length (Second Offence) | Mute Length (Third Offence) | 
| ----------------------------------- | ------------------------------- | ----------------------------------- | -------------------------------- | 
| Spam                                        | 5 Minutes                             | 1 Day                                        | Permanent                            |  
| Staff Disrespect                        | 1 Hour                                  | 7 Days                                      | -                                            |  
| Hackusting in Chat                   | 5 Minutes                             | 10 Minutes                               | -                                            |  
| Advertising                                | 1 Day                                   | 7 Days                                      | -                                            |  

If a players send a message while muted that counts as mute evasion which is bannable. Please check "Banning Players" for the length of the bans.  

## Find Proof, Players and some General Commands[¶](#finding-proof-and-finding-players "Permalink to this headline")

As a staff member when you are trying to find cheaters you need to first get into vanish by running the following command:  
```/sv```
When you are in vanish it is a good idea to go to the spectator gamemode. To do that run the following command:  
```/gmsp```
After you have vanished you will need to find a player to surveil. To do that you should run the teleportation command:  
```tp [PLAYER]```
Instead of filling in the player portion of the command you can hold tab and let it autocomplete with a randomly selected player. But you will have to stop holding tab before you teleport.  

Once you teleport to a player you can look at their behaviour. To determine what cheats/hacks the player could be using you can take lessons from the higher staff members. You would observe how the player is acting, if it looks like they are cheating and you have oriid then you can ban them. To learn how to ban please read "Banning Players". If the player was cheating and you banned them or the player wasn't cheating and you didn't ban them, you would repeat the teleporting procedure and check that the next player isn't cheating.  

When you want to stop checking if a player is cheating you usually would go to the spawn by running the following command:  
```/spawn```

Then you would be able to get out of the spectator gamemode by getting into the survival gamemode by running:  

```/gms```
Now you are ready to get out of vanish by running the vanish command again which is:  

```/sv```
Now you would be able to go playing the server normally. If you do see a person cheating and you aren't in vanish you can just ban them. To ban people you do not need to be in vanish.  
