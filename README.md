# Introduction
This is a sampke of code on how we can use GraphQL with ExpressJS and NodeJs

# Run 
run `npm install` and then `node .\rur-server.js` and then navigate to ` http://localhost:4000/`

# Test

You can use this query 

```code

mutation createMessageRequest {
  createMessage(input: {author: "andy", content: "hope is a good thing"}) {
    id
  }
}

query GetAll {
  quoteOfTheDay
  random
  rollThreeDice
  rollDice(numDice: 3, numSides: 5)
  getDie(numSides: 4) {
    rollOnce
    roll(numRolls: 3)
  }
  getMessage(id: "0bc220b605f8b072e3da"){
    content
  }
}

```
