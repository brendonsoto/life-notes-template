---
createdAt: 2024-03-04T12:37Z
modified:
tags:
- career
- interviewing
---
For all of these, either:
- set a time-limit of 30-45 minutes and talk through the process
- set a time-limit of 1-2 hours and figure out some way to document your process
- pick one sub-task to complete, set a time-limit (no longer than 15 minutes), record yourself working through the problem while talking it out, watch and reflect

## Free Rest APIs

- [Hacker News](https://github.com/HackerNews/API)


## Front End Practice

### Countries Table View

Use [REST Countries](https://restcountries.com/#endpoints-filter-response) to create a table for viewing, filtering, and searching countries.

### Hacker News clone

Use the [Hacker News API](https://github.com/HackerNews/API) to make a clone:
- [ ] list the top stories
- [ ] incorporate pagination
- [ ] link to comments
- [ ] filter by title
- [ ] filter by time (e.g. today, yesterday, past week)

### Mini Social Network

Use [JSONPlaceholder API](https://jsonplaceholder.typicode.com/guide/) to make a UI to show:
- a list of posts
	- a post should show: title and the user's name
- clicking a post should open a new page to show: title, user/author, body, comments

### Pokemon Viewer

Use [PokeAPI](https://pokeapi.co/) to make a UI to show:
- [ ] a grid view of card components showing pokemon
- [ ] each card should have:
	- [ ] number/order of pokemon (e.g. bulbasaur = 1, squirtle = 4, charizard = 7, etc.)
	- [ ] name
	- [ ] picture of pokemon
- [ ] clicking a card should show either:
	- [ ] open a new page with more information about the pokemon
	- [ ] open a modal to show more information on it



## Back End Practice

NOTE: Database may be optional. I guess practice first with in-memory data and then maybe with SQLite.

### Basic Blog

How would you design and develop a basic blog that supports:
- posts
- comments
- users

### Hacker News Clone

- [ ] GET /stories
	- [ ] id
	- [ ] title
	- [ ] userId
	- [ ] body
	- [ ] uploadedAt
	- [ ] upvotes
	- [ ] total number of comments
- [ ] GET /stories/{id}/comments
	- [ ] id
	- [ ] userId
	- [ ] uploadedAt
	- [ ] upvotes
	- [ ] text
- [ ] GET /user/{id}
	- [ ] id
	- [ ] username
	- [ ] email
- [ ] POST /stories
	- [ ] title
	- [ ] userId
	- [ ] body
- [ ] POST /stories/{id}/comments
	- [ ] userId
	- [ ] text
- [ ] How would you upvote a story/comment?

### Twitter Clone
