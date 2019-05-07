# ![LOGO](logo.png) Jokes One **flow**ground Connector

## Description

A generated **flow**ground connector for the Jokes One API (version 1.1).

Generated from: https://api.apis.guru/v2/specs/jokes.one/1.1/swagger.json<br/>
Generated at: 2019-05-07T17:42:36+03:00

## API Description

 Jokes One API offers a complete feature rich REST API access to its jokes platform.  This is the documentation for the world famous [jokes API](https://jokes.one/api/joke/).  If you are a subscriber and you are trying this from a console add 'X-JokesOne-Api-Secret' header and add your api key as the header value. You can test and play with the API right here on this web page. For using the private end points and subscribing to the API please visit https://jokes.one/api/joke/.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Gets `Joke of the Day`.<br/>
> Optional `category` param determines<br/>
> the category of returned joke of the day

*Tags:* `jod`

#### Input Parameters
* `category` - _optional_ - JOD Category

### Gets a list of `Joke of the Day` Categories.

*Tags:* `jod`

### Delete a joke. The user needs to be the owner of the joke to be able to delete it.

*Tags:* `joke`

#### Input Parameters
* `id` - _required_ - Joke ID

### Gets a `Joke` with a given `id`.

*Tags:* `joke`

#### Input Parameters
* `id` - _optional_ - Joke ID

### Update a joke

*Tags:* `joke`

#### Input Parameters
* `id` - _required_ - Joke ID
* `title` - _optional_ - title
* `text` - _optional_ - text
* `author` - _optional_ - Joke Author
* `tags` - _optional_ - Comma Separated tags

### Add a new joke to your private collection.

*Tags:* `joke`

#### Input Parameters
* `title` - _required_ - Joke Title
* `text` - _required_ - Joke Text
* `author` - _optional_ - Joke Author
* `tags` - _optional_ - Comma Separated tags

### Gets a list of `Joke` Categories.

*Tags:* `joke`

#### Input Parameters
* `start` - _optional_ - Response is paged. This parameter controls where response starts the listing at

### Get the list of jokes in your private collection.

*Tags:* `joke`

#### Input Parameters
* `start` - _optional_ - Response is paged. This parameter controls where response starts the listing at

### Gets a `Random Joke`. When you are in a hurry this is what you call to get a random famous joke.

*Tags:* `joke`

### Search for a `Joke` in Jokes One platform. Optional `category` , `author`, `minlength`, `maxlength` params determines the filters applied while searching for the joke.

*Tags:* `joke`

#### Input Parameters
* `category` - _optional_ - Joke Category
* `query` - _optional_ - keyword to search for in the joke
* `minlength` - _optional_ - Joke minimum Length
* `maxlength` - _optional_ - Joke maximum Length
* `author` - _optional_ - Joke Author
* `private` - _optional_ - Should search private collection? Default searches public collection.

### Add a tag to a given Joke.

*Tags:* `joke`

#### Input Parameters
* `id` - _required_ - Joke ID
* `tags` - _required_ - Comma Separated tags

### Remove a tag from a given joke.

*Tags:* `joke`

#### Input Parameters
* `id` - _required_ - Joke ID
* `tags` - _required_ - Comma Separated tags

## License

**flow**ground :- Telekom iPaaS / jokes-one-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
