

## Table of Contents

- [Features](#features)
- [Setup](#project-setup)
- [Edit Content](#how-to-edit-content)
- [Author](#author)
- [Contributing](#-contributing)
- [License](#-license)


## Project setup
```
npm install
```
### Compiles and hot-reloads for development
```
npm run serve
```
### Compiles and minifies for production
```
npm run build
```
### Lints and fixes files
```
npm run lint
```
### Customize configuration

## How to edit content
This template have a CMS support with CosmicJS. You can easily put your content there by creating and linking your CosmicJS account. 

In order to customize your portfolio, you must create a CosmicJS account and a new fresh bucket on it. Once done, you must update credentials of the **.env** file.

To do this, you just have to modify the variables contained in the ENV file (API token, bucket slug and read key).

```env
# CosmicJS 
VUE_APP_COSMICJS_TOKEN=" "
VUE_APP_COSMICJS_BUCKET_SLUG=" "
VUE_APP_COSMICJS_BUCKET_READ_KEY=" "
```

After that, you need to create the object type and data we will use. To do that properly and easily, you can import the json file, located [inside the data folder of this repo](https://github.com/hbollon/portfolio-vuejs/blob/master/data/portfolio-vuejs_import.json), by accessing import/export settings inside your bucket settings page.

Now, you can customize it with your data through CosmicJS interface!
## Author
