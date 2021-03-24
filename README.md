# mkdocs-quickstart

## Installation
```
brew install mkdocs
```

## Create Project
```
mkdocs new my-project
cd my-project

```
```
site_name: MkLorum
nav:
    - Home: index.md
```

## Serve
```
mkdocs serve
curl http://127.0.0.1:8000/
```

## Adding Pages
```
curl 'https://jaspervdj.be/lorem-markdownum/markdown.txt' > docs/about.md
```
```
site_name: MkLorum
nav:
    - Home: index.md
    - About: about.md
```

## Build
```
mkdocs build
echo "site/" >> .gitignore
mkdocs build --clean
ls site
```
```
about  fonts  index.html  license  search.html
css    img    js          mkdocs   sitemap.xml
```

## Deployment
- S3, CloudFront

## Authn
- Cognito, GSuite SAML SSO

## References
- https://www.mkdocs.org/#mkdocs
