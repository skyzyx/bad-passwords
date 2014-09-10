# [Bad Passwords](http://github.com/skyzyx/bad-passwords)

A list of the top 10,000 most-used passwords from hacked password lists.


## Requirements
### Required
The following software is **required** for Bad Passwords to run:

* [PHP] 5.3.0+

## Installation

### Bundle with Composer (recommended!)
To add Bad Passwords as a [Composer] dependency in your `composer.json` file:

```json
{
    "require": {
        "skyzyx/bad-passwords": ">=1.0"
    }
}
```

And include it in your scripts:

```php
require_once 'vendor/autoload.php';
```

## Contributing
To view the list of existing [contributors](/skyzyx/bad-passwords/graphs/contributors), run the following command from the Terminal:

```bash
git shortlog -sne --no-merges
```

### How?
Here's the process for contributing:

1. Fork Bad Passwords to your GitHub account.
2. Clone your GitHub copy of the repository into your local workspace.
3. Write code, fix bugs, and add tests with 100% code coverage.
4. Commit your changes to your local workspace and push them up to your GitHub copy.
5. You submit a GitHub pull request with a description of what the change is.
6. The contribution is reviewed. Maybe there will be some banter back-and-forth in the comments.
7. If all goes well, your pull request will be accepted and your changes are merged in.


## Authors, Copyright & Licensing

My intention is to release all rights to this documentation and make it available under the Public Domain. Unfortunately, in the U.S. it's not quite that cut-and-dry. So, I am dual-licensing this work under [CC0](LICENSE-CC0) and the [Unlicense](LICENSE-UNLICENSE). You can choose whichever license you would prefer to adhere to.

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/skyzyx/php-coding-standards">
    <span property="dct:title">Ryan Parman</span></a>
  has waived all copyright and related or neighboring rights to
  "<span property="dct:title">Bad Passwords</span>".
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="https://github.com/skyzyx/php-coding-standards">
  United States</span>.
</p>

  [PHP]: http://php.net
  [Composer]: https://getcomposer.org
