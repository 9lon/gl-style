# \<gl-style\>

gl-style for web components

## วิธีการใช้งานติดตั้ง

```
$ bower install 9lon-gl-styles --save
```

## วิธีการใช้งาน
import ไฟล์ gl-color ในหน้าที่่ต้องการใช้
```
 <link rel="import" href="bower_components/gl-styles/gl-color.html">
```
ให้คุณแทรก gl-color ใน แทรก style ในหน้าที่คุณต้องใช้งาน
```
<style is="custom-style" include="gl-color"></style>
```
ต่อมาก็แทรก css ดังตัวอย่างด้านล่างลงไปใน สไตล์ที่คุณต้องการจะเปลี่ยน 
```
    div.ex {
        color:var(--gl-primary-color);
    }
```
## Color variables
![alt text](http://i.imgur.com/DTyUDJv.png "gl-color")
```
        --gl-primary-color
        --gl-success-color
        --gl-info-color
        --gl-warning-color
        --gl-danger-color

        --gl-gray-darker-color
        --gl-gray-dark-color
        --gl-gray-color
        --gl-gray-light-color
        --gl-gray-lighter-color

        --gl-white-color

        --gl-primary-font-color
        --gl-success-font-color
        --gl-info-font-color
        --gl-warning-font-color
        --gl-danger-font-color
```