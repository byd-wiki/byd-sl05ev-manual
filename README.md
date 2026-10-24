# BYD SeaLion 05EV Service Manual

Some parts of BYD SeaLion 05EV Service Manual translated from Chinese.

Read: https://byd-wiki.github.io/byd-sl05ev-manual/


## Local Development

Based on [Hextra](https://imfing.github.io/hextra/) template for [Hugo](https://gohugo.io): https://github.com/imfing/hextra

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/byd-wiki/byd-sl05ev-manual.git

# Change directory
cd byd-sl05ev-manual

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.
