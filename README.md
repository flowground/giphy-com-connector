# ![LOGO](logo.png) Giphy **flow**ground Connector

## Description

A generated **flow**ground connector for the Giphy API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/giphy.com/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:55+03:00

## API Description

Giphy API

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Get GIFs by ID

> A multiget version of the get GIF by ID endpoint.

*Tags:* `gifs`

#### Input Parameters
* `ids` - _optional_ - Filters results by specified GIF IDs, separated by commas.

### Random GIF

> Returns a random GIF, limited by tag. Excluding the tag parameter will return a random GIF from the GIPHY catalog.

*Tags:* `gifs`

#### Input Parameters
* `tag` - _optional_ - Filters results by specified tag.
* `rating` - _optional_ - Filters results by specified rating.

### Search GIFs

> Search all GIPHY GIFs for a word or phrase. Punctuation will be stripped and ignored.  Use a plus or url encode for phrases. Example paul+rudd, ryan+gosling or american+psycho.

*Tags:* `gifs`

#### Input Parameters
* `q` - _required_ - Search query term or prhase.
* `limit` - _optional_ - The maximum number of records to return.
* `offset` - _optional_ - An optional results offset.
* `rating` - _optional_ - Filters results by specified rating.
* `lang` - _optional_ - Specify default language for regional content; use a 2-letter ISO 639-1 language code.

### Translate phrase to GIF

> The translate API draws on search, but uses the GIPHY `special sauce` to handle translating from one vocabulary to another. In this case, words and phrases to GIF

*Tags:* `gifs`

#### Input Parameters
* `s` - _required_ - Search term.

### Trending GIFs

> Fetch GIFs currently trending online. Hand curated by the GIPHY editorial team.  The data returned mirrors the GIFs showcased on the GIPHY homepage. Returns 25 results by default.

*Tags:* `gifs`

#### Input Parameters
* `limit` - _optional_ - The maximum number of records to return.
* `offset` - _optional_ - An optional results offset.
* `rating` - _optional_ - Filters results by specified rating.

### Get GIF by Id

> Returns a GIF given that GIF's unique ID

*Tags:* `gifs`

#### Input Parameters
* `gifId` - _required_ - Filters results by specified GIF ID.

### Random Sticker

> Returns a random GIF, limited by tag. Excluding the tag parameter will return a random GIF from the GIPHY catalog.

*Tags:* `stickers`

#### Input Parameters
* `tag` - _optional_ - Filters results by specified tag.
* `rating` - _optional_ - Filters results by specified rating.

### Search Stickers

> Replicates the functionality and requirements of the classic GIPHY search, but returns animated stickers rather than GIFs.

*Tags:* `stickers`

#### Input Parameters
* `q` - _required_ - Search query term or prhase.
* `limit` - _optional_ - The maximum number of records to return.
* `offset` - _optional_ - An optional results offset.
* `rating` - _optional_ - Filters results by specified rating.
* `lang` - _optional_ - Specify default language for regional content; use a 2-letter ISO 639-1 language code.

### Translate phrase to Sticker

> The translate API draws on search, but uses the GIPHY `special sauce` to handle translating from one vocabulary to another. In this case, words and phrases to GIFs.

*Tags:* `stickers`

#### Input Parameters
* `s` - _required_ - Search term.

### Trending Stickers

> Fetch Stickers currently trending online. Hand curated by the GIPHY editorial team. Returns 25 results by default.

*Tags:* `stickers`

#### Input Parameters
* `limit` - _optional_ - The maximum number of records to return.
* `offset` - _optional_ - An optional results offset.
* `rating` - _optional_ - Filters results by specified rating.

## License

**flow**ground :- Telekom iPaaS / giphy-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
