# Simple Template

A simple ColdBox MVC template

## License
Apache License, Version 2.0.

## Important Links

Source Code
- https://github.com/coldbox-templates/simple

## Docker Installation

To Use this application in a docker environment you can use the [ortussolutions/commandbox](https://hub.docker.com/r/ortussolutions/commandbox/) image, with the following configuration:

```bash
docker run -p 80:80 -p 443:443 -e "PORT=80" -e "SSL_PORT=443" -v "${PWD}:/app" -e BOX_INSTALL=true -e NV_API_KEY="your-key" -e NV_NAME="some-test" -e NV_TAGS="thing=one;other=bob"  ortussolutions/commandbox
```

## Quick Installation

Each application templates contains a `box.json` so it can leverage [CommandBox](http://www.ortussolutions.com/products/commandbox) for its dependencies.  
Just go into each template directory and type:

```
box install
```

This will setup all the needed dependencies for each application template.  You can then type:

```
box server start
```

And run the application.

---
