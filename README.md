# Simple Polls
> Super simple polls, made easy.

## Features

  - [ ] Create polls with custom response options
  - [ ] Share polls with shortened URLs
  - [ ] Vote and view results

## Technologies used

**Server:**
  - [FeathersJS](http://feathersjs.com/)
  - [NeDB](https://github.com/louischatriot/nedb)

**Client:**
  - [VueJS](http://vuejs.org/)

## Data model

Initially the only data saved are polls, containing a question, a short URL, responses, and their vote totals. Their structure is outlined below.

```js
{
  id: String,
  url: String,
  question: String,
  options: [
    {
      text: String,
      votes: Number
    }
  ]
}
```

## License

MIT
