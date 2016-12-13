# \<gl-style\>

gl-style for web components

## วิธีการใช้งานติดตั้ง

```
$ bower install 9lon-gl-styles --save
```
import ไฟล์ gl-styles ในหน้าที่่ต้องการใช้
```
 <link rel="import" href="bower_components/gl-styles/gl-styles.html">
```
ให้คุณแทรก gl-styles ใน แทรก style ในหน้าที่คุณต้องใช้งาน
```
<style is="custom-style" include="gl-styles"></style>
## วิธีการใช้งาน gl-color

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
## BG-Color variables
![alt text](http://i.imgur.com/s3gHS4Q.png "gl-bg-color")
```
        .gl-bg-primary
        .gl-bg-success
        .gl-bg-info
        .gl-bg-warning
        .gl-bg-danger
```
วิธีการใช้งาน
```
    <p class="gl-bg-primary">gl-bg-primary</p>
```
## Btn style and icon size
![alt text](http://i.imgur.com/CKClG9G.png "gl-color")
```
        .gl-btn-primary
        .gl-btn-success
        .gl-btn-info
        .gl-btn-warning 
        .gl-btn-danger 

        .gl-icon-size

```
## วิธีการใช้งาน  Btn style กับ  paper-button
```
       <paper-button raised class="gl-btn-warning">
                <iron-icon icon="favorite" class="gl-icon-size"></iron-icon>warning
       </paper-button>
```

## วิธีการใช้งาน gl-size

```
    <button class="ex-small">ex-small</button>
```
## Size class 
![alt text](http://i.imgur.com/00Ah52X.png "gl-color")
```
        .gl-ex-large
        .gl-large
        .gl-default
        .gl-small
        .gl-ex-small

```
## วิธีการใช้งาน  font size variables 

##  Font size variables 
```
       --font-size-default:        16px;
       --font-size-large:         ~20px
       --font-size-small:         ~14px
       --font-size-h1:            ~42px
       --font-size-h2:            ~34px
       --font-size-h3:            ~27px
       --font-size-h4:            ~20px
       --font-size-h5:             16px;
       --font-size-h6:            ~14px
```

### วิธีใช้งาน gl-table

![alt text](http://i.imgur.com/IZttsy2.png "gl-table-default")

Example

```
<table class="gl-table-default">
          <thead class="table-head">
            <tr>
              <th>1</th>
            </tr>
          </thead>
          <tfoot class="table-foot">
            <tr>
              <td></td>
            </tr>
          </tfoot>
          <tbody class="table-body">
            <tr>
             <td>1</td>
           </tr>
         </tbody>
      </table>
```
### วิธีใช้งาน gl-panel

![alt text](http://i.imgur.com/JN7xA5R.png "gl-panel")

Example

```
<div class="gl-panel-default">
    <div class="gl-panel-default-header">
        Header
    </div>
    <div class="gl-panel-default-content">
        content
    </div>
</div>
```

