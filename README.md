# Magexweb Core for Magento 2


## How to install & upgrade Magexweb_Core

### 1. Install via composer (recommend)

We recommend you to install Magexweb_Core module via composer. It is easy to install, update and maintaince.

Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require magexweb/module-core
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade

```
composer update magexweb/module-core
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Production mode:

```
php bin/magento setup:di:compile
```

### 2. Copy and paste

If you don't want to install via composer, you can use this way. 

- Download [the latest version here](https://github.com/magaxweb/module-core/archive/refs/heads/main.zip) 
- Extract `module-core-main.zip` file to `app/code/Magexweb/Core` ; You should create a folder path `app/code/Magexweb/Core` if not exist.
- Go to Magento root folder and run upgrade command line to install `Magexweb_Core`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
