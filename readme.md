<h6 align="center">
    <img src="https://i.imgur.com/QpAJLql.png" width="150"/>
</h6>

<h2 align="center">
    Laravel Mail Editor (Aka MailEclipse)
</h2>

<p align="center">
<a href="https://packagist.org/packages/ogestor/laravel-mail-editor" alt="sponsors on Open Collective"><img src="https://poser.pugx.org/ogestor/laravel-mail-editor/v/stable" /></a> <a href="https://packagist.org/packages/ogestor/laravel-mail-editor" alt="Sponsors on Open Collective"><img src="https://poser.pugx.org/ogestor/laravel-mail-editor/license" /></a> 
<a href="https://packagist.org/packages/ogestor/laravel-mail-editor" alt="Sponsors on Open Collective"><img src="https://poser.pugx.org/ogestor/laravel-mail-editor/downloads" /></a> 
</p>
<br/><br/>

MailEclipse is a mailable editor package for your Laravel applications to create and manage mailables using a web UI. You can use this package to develop mailables without using the command line, and edit templates associated with mailables using a WYSIWYG editor, among other features.

## WORK IN PROGRESS

Please note that this package is still under active development. We encourage everyone to try it and give feedback.

## Features

* Create mailables without using command line.
* Preview/Edit all your mailables at a single place.
* Templates (more than 20+ ready to use email templates).
* WYSIWYG Email HTML/Markdown editor.
* Suitable for laravel beginners.
* and many more... (promise).

## Requirements

* Laravel 5.6+.

## Installation

Via Composer

``` bash
$ composer require ogestor/laravel-mail-editor
```

The package will automatically register itself.

Publish configuration file and public assets:

``` bash
php artisan vendor:publish --provider="ogestor\mailEclipse\mailEclipseServiceProvider"
```

## Usage

[![Package tutorial](https://i.imgur.com/sBCiFyt.png)](https://www.youtube.com/watch?v=QFgEGNBY3FI)


After setting up the package as described above, you can now access the application by visiting the `/maileclipse` route (considering the default url is `maileclipse` in the config file). You can modify it to whatever you want as per your needs.

![maileclipse-img](https://i.imgur.com/cWD5odh.png)

## Change log

Please see the [changelog](changelog.md) for more information on what has changed recently.

## License

MIT license. Please see the [license file](LICENSE) for more information.

## Screenshots

![maileclipse-new-mailable](https://i.imgur.com/AiMEtY0.png)

![maileclipse-templates](https://i.imgur.com/siqxWVa.png)

![maileclipse-templates-create](https://i.imgur.com/8OQrEIS.png)

