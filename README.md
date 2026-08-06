### Card format

```js
{
  id:'str', //this is a unique lowercase identifier for linking cards
  name:'str', //this is the title that actually appears on the card
  col:'str', //this places it in the correct column, current options are: ['people', 'places', 'evidence', 'questions']
  tag:'str', //this is for other clear labels like 'dead'
  session:int, //tis is for filtering, should use the first/most important appearance/occurence
  lines:['str', 'str'...], //currently unused, this is a bullet point list of notes
  links:['str','str'...] //this links using the id
}
```