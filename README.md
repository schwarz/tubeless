# Tubeless

Tubeless is a simple tool to aggregate YouTube videos by multiple channels without a Google account.

The channels you want to follow are stored in the URI (akin to Reddit's multireddits). Through query string parameters you can also specify how many videos you want to fetch per channel and how many you want to display (sorted by how recently they were published). The parameters for this are `per` and `total`. Finally, you can hide the easy setup by setting the `setup` parameter to `false`.

Watched videos are distinguishable by the color of visited links.

For further customization I've included comments in the source, although Tubeless is perfectly usable without diving in.

## Dependencies

Everything you need to get started is included in the repository except for jQuery, which is loaded from the official CDN.

## Alternatives

It's possible to add a channel's feed to your news reader and get new videos that way. See https://www.youtube.com/t/rss_feeds for more information.

## License

Tubeless is released under the MIT license. See LICENSE for details.
