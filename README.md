# craft-alibaba-oss
Alibaba OSS integration for Craft CMS
This plugin provides an [Alibaba OSS](https://www.iusman.com) integration for [Craft CMS](https://craftcms.com/), with this plugin we can create an Alibaba OSS volume type for Craft CMS.

## Requirements

- PHP 8.0.2 or later
- Craft CMS 4.0 or later

## Installation

You can install this plugin with Composer.

#### With Composer

Open your terminal and run the following commands:

```bash
# go to the project directory
cd /path/to/my-project

# tell Composer to load the plugin
composer require usman/craft-alibaba-oss

# tell Craft to install the plugin
./craft plugin/install craft-alibaba-oss
```

## Setup

To create a new Aliyun OSS filesystem to use with your volumes,

- Login admin, visit **Settings** → **Filesystems**,
- Press **New filesystem**.
- Select “Alibaba OSS” for the **Filesystem Type**
- Setting and configure as needed.
