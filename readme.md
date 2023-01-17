# Performance basics

This is a small exercise to introduce the idea of perfomance in programming.

Oh no! Something went wrong with our database! Luckily you were able to record a database dump of JSON files
Can you reconstruct which skills each user had and combine the data?

## Todo

- Download or clone this repo
- Write a script where you import `skills_10.json`, `users_10.json` and `users_skill_50.json`
- In this script combine the data from the json file into a single array of users with each users containing an array of skills

```js
[
  {
    id: 1,
    first_name: "Sigismond",
    last_name: "Ipplett",
    email: "sipplett0@indiegogo.com",
    skills: [
      { id: 49, skill: "Hydrology" },
      { id: 33, skill: "Electrical Controls" },
      { id: 9, skill: "Training" },
      { id: 15, skill: "Ultiboard" },
      { id: 24, skill: "FP7" },
    ],
  },
  {
    id: 2,
    first_name: "Sofia",
    last_name: "Dyter",
    email: "sdyter1@nsw.gov.au",
    skills: [
      { id: 7, skill: "International Business" },
      { id: 14, skill: "CVM" },
      { id: 25, skill: "Global Marketing" },
      { id: 92, skill: "MGCP" },
      { id: 89, skill: "Zumba" },
    ],
  },
  ... 8 more items
];
```

- Find a way to measure how long your script takes to execute
- Commit your current solution
- Now try your solution with: `skills_100.json`, `users_100.json` and `users_skill_500.json`
- What effect does the increase in data have on your execution time?
- Can you think of way to optimize your code?
