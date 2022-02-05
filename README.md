# magento2-uifrontend

It's implementing the ui grid component from adminhtml to frontend side.

![Image 1](https://i.imgur.com/5HZk9CQ.png)

## How to install?

#### Via Composer

If you try to install via composer, just require your project to the module by running this command :

```
composer require fiko/magento2-uifrontend
```

#### Manually

1. Download this repo
2. Create a Directory `app/code/Fiko/UiFrontEnd`
3. Copy downloaded repo to this directory

Once you download it (both composer or manually), just run this commands to apply this module to your project :

```
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```

## How to use?

Simply just add extra css to the layout/grid.

```
<head>
    <css src="Fiko_UiFrontEnd::css/grid.css" />
</head>
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/) &copy; 2022
