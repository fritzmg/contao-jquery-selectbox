[![](https://img.shields.io/maintenance/yes/2015.svg)](https://github.com/fritzmg/contao-jquery-selectbox)
[![](https://img.shields.io/packagist/v/fritzmg/contao-jquery-selectbox.svg)](https://packagist.org/packages/fritzmg/contao-jquery-selectbox)
[![](https://img.shields.io/packagist/dt/fritzmg/contao-jquery-selectbox.svg)](https://packagist.org/packages/fritzmg/contao-jquery-selectbox)

Contao jQuery selectBox
===================

Simple extension to provide the [jQuery selectBox plugin by marcj](https://github.com/marcj/jquery-selectBox) in Contao.

## Styling

If you want to create your own styles without overriding the default one, create your own `j_selectbox` template and remove or disable the line `$GLOBALS['TL_CSS'][] = …` in the PHP section of the template.

## Configuration

In order to configure the default initialization, create your own `j_selectbox` template and change the script part. See the [documentation of the original plugin](https://github.com/marcj/jquery-selectBox#settings) for all available options.
