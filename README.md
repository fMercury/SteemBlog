# SteemBlog

## Install

`git clone https://github.com/fMercury/SteemBlog`

`npm install`

## Config

Edit the config file with the blog title, social media urls and username in steemit inside the src folder.

Example:
```
{
  "blogTitle": "X SteemBlog",
  "facebookLink": "https://fb.com/X",
  "twitterLink": "https://twitter.com/X",
  "linkedinLink": "https://ar.linkedin.com/in/X",
  "githubLink": "https://github.com/X",
  "steem": {
    "username": "X",
    "fromPost": 10000
  }
}
```

Edit the index.html file on src folder with teh correct values on header tag.

## Develop

Run `npm start` to develop and enable the hot reloading.

## Build

Run `npm run build` to build the production version.
