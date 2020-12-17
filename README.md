# x-redirect

A http(s) interface to custom url scheme.

## Usage

Deploy index.html somewhere (e.g. `myhost.com/index.html`)
Then create http(s) links that redirect to custom URI scheme links:
e.g. 
`https://myhost.com?x-devonthink-item://870E7555-1953-45D6-B143-B2D857F8FD0C` will redirect to `x-devonthink-item://870E7555-1953-45D6-B143-B2D857F8FD0C`
`https://redirect.domain.com?obsidian://open?vault=MyVault&file=Home.md` will redirect to `obsidian://open?vault=MyVault&file=Home.md`

## Motivation

Allowing custom url scheme to work cross-platform on notion.so.
