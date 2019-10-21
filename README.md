## dns64/nat64 Service

### dns64 servers

Set your DNS resolvers to use the following DNS servers:
- 2403:fdc0::6464
- 2403:fdc0::6666

These servers will return A/AAAA using the NAT64 prefix **2403:780:fe00:7175::/96**

Alternatively, you can use [Google's Public DNS64 service](https://developers.google.com/speed/public-dns/docs/dns64)
- 2001:4860:4860::6464
- 2001:4860:4860::64

Google's DNS64 servers use the WKP (Well Known Prefix) **64:ff9c::/96** (per [RFC6146](https://tools.ietf.org/html/rfc6146))

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

