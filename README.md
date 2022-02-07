# MapTiler Styles
Visual front-end framework of MapTiler brand based on Bootstrap
## Icons
We use [material icons](https://fonts.google.com/icons?selected=Material+Icons) for all the icons, with some custom ones made by our designer. 
### Icons structure

 `/extra` folder contains all the edited icons or the ones that need to be editable with css and are being used in different components. 
 
 `/SVG` folder contains all the `.svg` files of our icons
 
 `icon.svg` file contains all our icons compiled and ready to be used as inline svgs, this is the preferred way of using icons because you can change them with CSS. 

Add icon as an inline svg from icon sheet(icon.svg) with all icons, this option can be styled.
```
<svg version="1.1" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><use href="/styles/icon.svg#icon_ID"></use></svg>
```
or as a file
```
<img src="/icon/SVG/icon_name.svg" alt="icon">
```
All icons with names can be viewed in demo.html accessible manually.

### Adding an icon

Choose an icon from the material icon resource, then add svg file to the `/SVG` folder, then add the same icon to `icons.svg` with unique id so it can be used both ways.



