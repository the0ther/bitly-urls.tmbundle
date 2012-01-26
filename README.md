Bitly URLs Textmate Bundle
==========================
:)

INSTALLATION
------------
    cd ~/Library/Application Support/TextMate/Bundles/
    git clone git://github.com/winterl/bitly-urls.tmbundle.git

API KEY
-------
A key has been provided, but if you prefer to use your own API key (https://bitly.com/a/your_api_key/), add:

* TM_BITLY_LOGIN -- `login`

* TM_BITLY_API -- `API key`

in `TextMate > Preference > Advanced > Shell Variables`

COMMANDS
--------
* To shorten a URL -- `shift ctrl 0`

* To expand a URL -- `shift ctrl 9`

* To view click statistics (countries) -- `shift ctrl 7`

* To view click statistics (referrers) -- `shift ctrl 6`

### Working but not formatted

* To view click statistics -- `shift ctrl 8`

unformated json returns clicks, clicks per minute, and clicks per day

