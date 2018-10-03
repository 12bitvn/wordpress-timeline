# WordPress Timeline

The brief history of WordPress.

## Contribute

Install packages

```shell
yarn install
```

Start the server to serve static files.

```shell
yarn start
```

Add your milestones in `public/timeline.json`

An example of milestone in `json` format:

```json
{
    "media": {
        "url": "/img/matt-first-post.png",
        "caption": "Matt's first post",
        "credit": "<a href='https://ma.tt/2002/02/testing-new-system/'>https://ma.tt/2002/02/testing-new-system/</a>"
        },
        "start_date": {
        "day": "06",
        "month": "02",
        "year": "2002"
        },
        "text": {
        "headline": "Matt Mullenweg's first post",
        "text": "<p>Matt Mullenweg published his <a href='https://ma.tt/2002/02/testing-new-system/' target='_blank'>first blog post</a> with Movable Type.</p>"
    }
}
```


