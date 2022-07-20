# Fuse.js for Google Apps Script

This project is unofficial of https://github.com/krisk/Fuse.

Script ID: `1JvIG6LaQ3F2SeLQ9TVdHsA2H8lcF-CB2UxvRfyKPGhV8QkBeSjjjlxo9`

## Adding the library to your project

Select "Resources" > "Libraries..." in the Google Apps Script editor. Enter the project key (1JvIG6LaQ3F2SeLQ9TVdHsA2H8lcF-CB2UxvRfyKPGhV8QkBeSjjjlxo9) in the "Find a Library" field, and choose "Select". (If you have copied the library, enter instead the project key of your copy.) Select the highest version number, and choose Cheerio as the identifier. (Do not turn on Development Mode unless you know what you are doing. The development version may not work.) Press Save. You can now use the Fuse (fusegs) library in your code.

## Usage

```js
const sampleFunction = () => {
  const Fuse = Fusegs.Fuse; // import Fuse.js
  const list = [...]; // Search Array List
  const fuse = new Fuse(list,{keys: ["title"]});
  console.log(fuse.search("Code"))
}
```

Please check out how to use Fuse.js at [fusejs.io](https://fusejs.io/)
