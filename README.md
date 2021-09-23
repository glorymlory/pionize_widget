# pionize_widget

Pionize widget is a ... .

## Deno 
https://pionize-widget-kbgml.ondigitalocean.app/

## Prerequisites

- {provided-client-id} - we supply you with unique customer token that is needed for proper widget functioning.

## Usage

Find the place in your website you want to integrate this widget. 
Insert this code : 

```html
    <div class="container">
        <iframe class="responsive-iframe" src="https://smarthome.pionize.de/smarthome-finden/widget/999999999"></iframe>
    </div>
```

``` css
<style>
.container {
  position: relative;
  overflow: hidden;
  /* width: 100%; */
  padding-top: 550px; 
}

/* Then style the iframe to fit in the container div with full height and width */
.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
  border: 0;
}
</style>
```

## Flow 

![swimlanes-62c5f7050bbfe8e9200214e81f2fd41c](https://user-images.githubusercontent.com/55086326/128915276-98f2d7d3-9feb-43c6-b872-b2a21ec45435.png)

title: Widget flow

Widget -> Widget: generate unique session/user id on upload
Widget -> Backend: send user`s answer with cutstomer id
note:
_customer id_ - token of a blog/website

Widget --> Frontend: redirect user to website with session/user id

Frontend -> Backend: login/register with session/user id

## License
[MIT](https://choosealicense.com/licenses/mit/)
