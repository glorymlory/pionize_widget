# pionize_widget

Pionize widget is a ... .


## Prerequisites

- {provided-client-id} - we supply you with unique customer token that is needed for proper widget functioning.

## Usage

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.
Find the place in your website you want to integrate this widget. 
Insert this code : 

```html
    <div class="container">
        <iframe class="responsive-iframe" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen src="http://localhost:3000/smarthome-finden/widget/{provided-client-id}"></iframe>
    </div>
```

``` css
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
```

## License
[MIT](https://choosealicense.com/licenses/mit/)