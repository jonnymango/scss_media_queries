# scss_media_queries
Simple SCSS mixin set up for media queries

## Usage
```
.foo {
@include mobile {
    background: green;
    @include mobile {
	background: yellow;
    }
    @include mobile {
        background: blue;
    }    

}
```
