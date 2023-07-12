# @nkzw/safe-word-list

This package contains a list of about 2900 of the most used safe words in English with at least three characters or more.

## Installation

```
npm install @nkzw/safe-word-list
```

## Usage

```js
import words, { getRandomWord } from 'safe-word-list';

console.log(words.slice(10, 5)); // ["absolutely", "absorb", ...]

getRandomWord(); // "beautiful"
```
