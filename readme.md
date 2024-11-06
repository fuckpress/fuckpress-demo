# FuckPress Demo

<p align="center">
  <img src="https://github.com/user-attachments/assets/1aa03ce3-94ea-49c5-9860-89d0d33fda26" width=150>  
</p>

Made with [FuckPress](https://github.com/fuckpress/fuckpress-core)

## Structure

As you can see, you only need the **fp-admin.yaml** file. 

|item|description|
|:--|:--|
|fp-admin.yaml| file with data to be used in the web|

## Requirements

- Nodejs
  - Just the first time and or for development. 
  - The result will not require nodejs because the publish result are static files like html, css, js, etc

## Install

```
npm install -g github:/fuckpress/fuckpress-core
```

## Create new site

```
fuckpress --new-site acme
cd ./acme
```

## Start

```
fuckpress --start
```

Go to http://localhost:2708 and you will see the demo

<p align="center">
 <img src="https://github.com/user-attachments/assets/2ecc6d95-efd3-49f8-a3d6-9b88d3482411" width=500>
</p>

## Publish

This command allow you to generate a static build (html, js, css, etc) on any folder. 

In this example we will generate the static page in a **docs** folder to use github page

```
fuckpress --publish --output=docs
```

## Custom theme

For custom theme, just create a folder called theme at the root with the common static content : index.html, css, js, etc

## Advanced usage

- https://github.com/fuckpress/fuckpress-core

## Contributors

<table>
  <tbody>    
    <td>
      <img src="https://avatars0.githubusercontent.com/u/3322836?s=460&v=4" width="100px;"/>
      <br />
      <label><a href="http://jrichardsz.github.io/">JRichardsz</a></label>
      <br />
    </td>
  </tbody>
</table>
