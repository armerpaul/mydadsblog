## Commands

### Develop locally

```
npm run start
```

Starts up the hugo server locally. No need to compile the sass, as hugo does that already.

### Create a post

Create a new markdown file for a new post. Make sure to set the date after it's created!

To create a text only post, run :
```
npm run post --slug=my-slug-name
```

To create a post with images or other attachments, run:
```
npm run post+ --slug=my-slug-name
```

### Deploy

Deploys to github pages (see the [`public`](https://github.com/armerpaul/mydadsblog/tree/public) branch).

```
npm run deploy
```