# Get all links from markdown file [![GoDoc](https://godoc.org/github.com/nikitavoloboev/markdown-parser/parser?status.svg)](https://godoc.org/github.com/nikitavoloboev/markdown-parser/parser) [![Thanks](https://img.shields.io/badge/Say%20Thanks-💗-ff69b4.svg)](https://www.patreon.com/nikitavoloboev) 

## Description 📕
This is a simple Go library that will parse a given markdown file and grab all links from it and put it into a hashmap `map[string]string` to use.

## Install 💎
With a [correctly configured](https://golang.org/doc/install#testing) Go toolchain :

`go get -u github.com/nikitavoloboev/markdown-parser/parser`

## Examples 📌
You can see this library being used in [Aflred Awesome Lists](https://github.com/nikitavoloboev/alfred-awesome-lists) to grab all links from [Sindre's awesome list](https://github.com/sindresorhus/awesome) and filter the results in Alfred.