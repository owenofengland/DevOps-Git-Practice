Agile Software Development and DevOps Git Practice
==================================================

## Wannacry Ransomware

[Link to article](https://www.csoonline.com/article/3227906/ransomware/what-is-wannacry-ransomware-how-does-it-infect-and-who-was-responsible.html)

Wannacry was a ransomware worm that infected a large number of computers in 2017, encrypting a users hard drive, and requiring them to pay in order for it to be decrypted. This particular worm is interesting as it is believed that the vulnerability that was exploited was originally discovered by the NSA, but the worm itself was linked to an organization tied to the North Korean government. The NSA discoverd the vulnerability (injection of packets to execute code, specifically within Windows Server Message Block protocol), yet they did not inform anyone about the issue, instead devloping their own code to exploit it. This code was then stolen and used to develop the hack, by which time Microsoft had released a patch. But as many users do not apply updates in a timely fashion, many were still left vulnerable, and fell victim to the attack (and people/business still fall victim to it). Basically, the moral of the story is apply official updates as soon as possible.

### Additional Comments by Haomiao Han (hh1519)
It is interesting that despite the fact that Microsoft has already discovered the vulnerability and released an update that fixes the vulnerability, many users decide - whether intentionally or unintentionally - not to apply that update. I wonder if that has something to do with Microsoft's design on Windows updates. Essentially, Windows Updates are seen as not being user friendly and we often see memes regarding how Windows Updates can interrupt user's work, which could be annoying at times. I think it may be a good opportunity for Microsoft to consider improving the Windows update process and inform users in a better way.


### Additional Comments by Esther Sun (es4271)
I think it is interesting and a bit scary that the U.S. National Security Agency had already discovered this vulnerability before the ransomware was created and did not report it. It makes me wonder what other vulnerabilities they know about but aren't releasing to the public to help them browse the web safely. I think it's also interesting that the patch to prevent this malware was already realized before the attacks even began, showing again further reason to keep your machines up to date with updates.
