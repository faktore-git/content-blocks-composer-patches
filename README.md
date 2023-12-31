| :exclamation: This patch is to be considered obsolete for the time being. |
|---------------------------------------------------------------------------|

# content-blocks-composer-patches

Provides composer patches to use EXT:content_blocks within
TYPO3 v12 in combination with EXT:container.

## Usage:

Add package as a dependency:

```
composer require faktore/content-block-composer-patches
```

To allow composer applying patches from 3rd-party-dependencies
(not defined in root composer.json) the option _enable-patching_
must be set to _true_ in the _extra_-section of your _composer.json_,
either via:

```
composer config extra.enable-patching true
```

or:

```
{
  ...
  
  "extra": {
    ...
    
    "enable-patching": true
  }
}
```

## CAUTION

Currently only works with version 0.1.3 of content blocks. 
There is currently no known reason to have to apply these patches. 
