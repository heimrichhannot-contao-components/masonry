# Masonry Contao component

[![Latest Stable Version](https://poser.pugx.org/heimrichhannot-contao-components/masonry/v/stable)](https://packagist.org/packages/heimrichhannot-contao-components/masonry)
[![Total Downloads](https://poser.pugx.org/heimrichhannot-contao-components/masonry/downloads)](https://packagist.org/packages/heimrichhannot-contao-components/masonry)

Shim repository for [Masonry](https://github.com/desandro/masonry) as [Contao Component](https://github.com/contao-components/installer).


## Install

```
composer require heimrichhannot-contao-components/masonry
```


## Config

Add the following to your config (keep keys to prevent double integration):

### Contao 4

```
$GLOBALS['TL_JAVASCRIPT']['huh_components_masonry'] = 'assets/masonry/dist/masonry.pkgd.min.js|static';
```

### Contao 3

```
$GLOBALS['TL_JAVASCRIPT']['huh_components_masonry'] = 'assets/components/masonry/dist/masonry.pkgd.min.js|static';
```


## Internal
 
Update Library:

```
svn export https://github.com/desandro/masonry.git/trunk/dist
```