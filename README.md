## Card format

```js
{
  id: 'str',       // unique lowercase identifier for linking cards
  name: 'str',     // the title that actually appears on the card
  col: 'str',      // which column it goes in: 'people', 'places', 'evidence', or 'questions'
  tag: 'str',      // for other clear labels like 'dead'
  session: 1,      // for filtering, use the first/most important appearance
  status: 'str',   // OPTIONAL, questions only: 'partial' or 'answered'
  lines: ['str'],  // bullet point list of notes
  links: ['str']   // ids of related cards
}
```

