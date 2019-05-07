# ![LOGO](logo.png) Tweet summarization APIs MSP Connector

## Description

A generated MSP connector for the Tweet summarization APIs API (version 0.0.1).

Generated from: https://api.apis.guru/v2/specs/apitore.com/tweetSummarizationApis/0.0.1/swagger.json<br/>
Generated at: 2019-05-07T11:17:06+03:00

## API Description

Tweet summarization.<BR />[Endpoint] https://api.apitore.com/api/27

## Authorization

This API does not require authorization.

## Actions

### Summarize tweets.

> Tweet summarization API.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/twitter-response">twitter-response</a><BR />&nbsp; Class: com.apitore.banana.response.twitter.TwitterSummarizeResponseEntity<BR />

*Tags:* `twitter-simple-summarize-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `q` - _required_ - Search query
* `sinceId` - _optional_ - Get after this id.
* `maxId` - _optional_ - Get before this id.
* `iter` - _optional_ - Numof search requests. Return up to 100 x iter tweets.
* `num` - _optional_ - Numof summarization tweets.

## License

flowground :- Telekom iPaaS / apitore-com-tweet-summarization-apis-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
