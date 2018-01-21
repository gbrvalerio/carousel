# Carousel

A Flutter simple Carousel Widget.

## Usage

As simple as using any flutter Widget. The Carousel package hides all the complexity (almost none, it's Flutter!) of implementing a carousel.

####Example:
```dart

new Carousel(
  children: [
    new NetworkImage('https://pbs.twimg.com/profile_images/760249570085314560/yCrkrbl3_400x400.jpg'),
    new NetworkImage('https://webinerds.com/app/uploads/2017/11/d49396_d9c5d967608d4bc1bcf09c9574eb67c9-mv2.png')
  ].map((netImage) => new Image(image: netImage)).toList(),
)

```
This code snippet creates an Carousel that contains both the logos of Flutter and React native, as an example.

## Credits

Developed by Gabriel Valério <gbrvalerio@gmail.com>

## Contributing

Feel free to help!

