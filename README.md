# Experimental-features Canopsis Brick

## Description

Experimental features for Canopsis Frontend

## Screenshots



## Installation

You need to clone the git repository and copy directory to Canopsis path

    $ git clone https://git.canopsis.net/canopsis-ui-bricks/brick-experimental-features.git
    $ cp -r brick-experimental-features $CANOPSIS_PATH/var/www/canopsis

Then, you need to enable the brick

    $ su - canopsis
    $ webmodulemanager enable brick-experimental-features

You can see enabled bricks

    $ su - canopsis
    $ webmodulemanager list
    [u'core', u'uibase', u'monitoring', ..., **u'brick-experimental-features'**]

## Usage

See [Howto](https://git.canopsis.net/canopsis-ui-bricks/brick-experimental-features/blob/master/doc/index.rst)

## Continuous Integration

### Tests

The last build was not a full build. Please use the "full-compile" npm script to make test results show up here.

### Lint

Tested on commit : 9f895a7.

| Target | Status | Log |
| ------ | ------ | --- |
| Lint   | :ok: OK |  |


## Code Notes

### TODOS



### FIXMES



## Additional info

Minified version : 3 files (size: 20K)
Development version : 1 files (size: 8,0K)
