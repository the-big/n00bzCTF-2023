```
         ___   ___  _         _____ _______ ______ 
        / _ \ / _ \| |       / ____|__   __|  ____|
  _ __ | | | | | | | |__ ___| |       | |  | |__   
 | '_ \| | | | | | | '_ \_  / |       | |  |  __|  
 | | | | |_| | |_| | |_) / /| |____   | |  | |     
 |_| |_|\___/ \___/|_.__/___|\_____|  |_|  |_|     
```

# The Power of Google Lens for Geoguessr OSINT Challenges (Damn, Mission Moon, Lost)

### Damn

*The problem*: `Damn bro, Dam! -- Note: Find out the city that this dam is in. Flag format is n00bz{City_Name} Author: NoobMaster`

*The file*:

![img](https://cdn.discordapp.com/attachments/982094827170713712/1117620373933019226/dam.png)

1. Whenever I'm given an image for an OSINT challenge, I always like to use Google Lens to either 1) discover the origin of the image (preferred) or 2) find out similar images that hints at its whereabouts. In this case, the latter fits this problem:

![img](https://cdn.discordapp.com/attachments/982094827170713712/1117621570219814922/image.png)

2. We can observe that there is one perfect match ![perfil.com](https://www.perfil.com/tags/Rusia), however once you get into the webpage, there is no article or information that hints at its location. One of the joys of solving OSINT challenges is that you learn to master these basic tools. You can utilize Google Lens to its full potential when you realize you can crop the portion you would like to search for.

![img](https://cdn.discordapp.com/attachments/982094827170713712/1117622521932562462/image.png)

3. Just by reducing the crop window, we can see that we can more results, and one particular result stands out to me: the article from ![Digital Journal](https://www.digitaljournal.com/world/ukraine-dam-destruction-a-consequence-of-russian-invasion-un-chief/article).

![img](https://cdn.discordapp.com/attachments/982094827170713712/1117622873557835946/image.png)

4. Viola! We can identify from the image above that this appears to be the **Kakhovka dam**. Sweet, let's find the city it resides in.

![img](https://cdn.discordapp.com/attachments/982094827170713712/1117623380745650196/image.png)

5. With the address being "Новокаховське шосе, 3 м, Nova Kakhovka, Kherson Oblast, Ukraine, 74900," we can deduce that the city is either "Nova Kakhovka" or "Kherson Oblast." After further investigation, Kherson Oblast appears to be a province within Ukraine, therefore we can say for certain the city would be Nova Kakhovka.

6. The flag format indicates us to put it in n00bz{City_Name} format, so let's do that: `n00bz{Nova_Kakhovka}`

### Mission Moon
*The problem*:

*The file*:

### Lost
*The problem*:

*The file*:
