# Code-Blocks-Traditional-Chinese
The project for translating Code::Blocks into zh_TW.  

## Language
Traditional Chinese (Chinese, Taiwan)  

## Tools
We use [Poedit](https://poedit.net/) as translating tool.  
You can use it under all platform.  

## Usage
### For normal user
1. Download [zh_TW.mo]().  
2. Go to Code::Blocks share directory.(Ex: "C:\Program Files(x86)\CodeBlocks\share\CodeBlocks")  
3. Create an directory named "locale".  
4. Go into "locale", and create an directory named "zh_TW".  
5. Go into "zh_TW", copy "zh_TW.mo" in it and rename it to "codeblocks.mo".  

If you are using Unix-based or Linux-based system, you might create an directory named "LC_MESSAGES" in "zh_TW" and put "codeblocks.mo" in "LC_MESSAGES".  

### For translator
Just download [zh_TW.po](), and use poedit to edit it.  
It's welcome to send me a pull request or open an issue if you think the translation has some mistake.  

## Why not using Crowdin, Transifex or launchpad(Offical)?
Crowdin and Transifex don't have free plan, I do not have enough budget to use those platform.  
Also, this translation have more than 9000 strings, I will have to pay at least 79 dollars per month.It's over my budget.  
Launchpad? Well, the older version of this translation seems that it have not been maintained for a long time, and the platform is not good for translation, so I decided to use github as translation platform.  
Of course, There might having a better place, so if you found it, please tell me about it, thanks.  

## License
It's free to use under the license of Code::Blocks.  