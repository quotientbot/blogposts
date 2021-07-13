Quotient's Tagcheck has proven to be a very useful functionality for esports servers who host regular scrims or tournaments. It basically allows you to setup tagchecks in a channel where users will then paste their registration formats and Quotient will accept or deny their formats according to the number of required mentions. 

Command Structure:

```
[tagcheck|tc]
|
└───── set
|
└───── remove
|
└───── config
|
└───── autodelete
```

![image](https://user-images.githubusercontent.com/72350242/125495587-0da4fbcc-902d-4b09-8dc5-00c66cfa5f90.png)


- **tagcheck set #channel**: Set Quotient's tagcheck in the mentioned channel.
- **tagcheck remove #channel**: Remove mentioned channel from tagcheck channels.
- **tagcheck config**: Get Quotient's tagcheck configuration for the server.
- **tagcheck autodelete #channel**: Enable/Disable auto delete wrong formats for a channel.

Usage Example:

![image](https://user-images.githubusercontent.com/72350242/125495954-6669accb-6343-4272-aa3d-91ab8d628703.png)

![image](https://user-images.githubusercontent.com/72350242/125495999-09bfcc76-084b-48d3-a26f-a4adff4cc5e0.png)


**FAQ**

1. What is **quotient-tag-ignore**? <br/>
Ans. It is a role created by Quotient when you setup tagchecks, you can give this role to any user whose messages you want to be ignored in tagcheck channels. Means if you give it to yourself and then you send a message in tagcheck channel, Quotient will ignore your message.

2. Can I rename **quotient-tag-ignore** role? <br/>
Ans. No you can't , it won't work if you rename it.

3. How to set required mentions or required tags in tagcheck channel? <br/>
Ans. You can use the command like: <br/>

**tagcheck set #channel 4** to set 4 as the number of required mentions. It is 0 by default. You can replace 4 with any number below 10 to set that as required mentions for that channel. <br/>
If you already have a tagcheck channel and you want to change its required mentions, you will have to remove it first. Use the following commands: <br/>
<br/>
- **tagcheck remove #channel** <br/>
- **tagcheck set #channel 0** (replace 0 with number of mentions you want to set.) <br/>

4. Can I set multiple tagcheck channels in one server? <br/>
Ans. Yes you can set unlimited tagcheck channels in a server if you have Quotient Premium. If you are on free tier, you only set 1 tagcheck channel.
You can Quotient Premium here: https://quotientbot.xyz/premium
