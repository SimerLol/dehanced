# Dehanced Api
Cli tool to bulk generate nfts using Neural Style Transfer and AI learning (AI Learning is not included)
---
![unknown](https://user-images.githubusercontent.com/76672732/181918665-bee9f9af-f631-492c-ba91-4dbaacbd6578.png)
> The code was written locally so that I could generate everything with full power on the spot. I will clean it all up with some gitignores and put it here (no version control LOL) If you want the code early, dm me on discord Simer#7544 and I'll zip send it to you :)

---

## How does the code work?
There is a single `index.js` file of which on the top has user configuration settings. You set the following:
- Input image `True / False` and assets load directory (relative)
- Usage of a `CSV` file or `Array`?

> Regardless of which bulk generation data input you pick, whether CSV or Array, the code will read both in the `phrase`, `stylenumber` and `strength` format.
>> The Phrase is the text you enter for the code to use its ai learning for <br>
>> The Stylenumber is an int ranging from `1-18` <br>
>> The Strength determines how much impact the input image has on the output; `LOW` `MEDIUM` `HIGH` <br>

> This is an example of a CSV file: 
>>>  `Apple, 12, Medium` <br> `Banana, 8, HIGH` <br> `WOOOOOOO, 2, LOW ` <br>

> This is an example of the Array:
>>> `entries["Apple,12,Medium", "Banana,8, HIGH", "WOOOOOOO,2, LOW]` <br>
>>> 
---
# Installation
> (You need to have Node installed)
Install dependencies `npm i` 
Run `node index`

MIT License
