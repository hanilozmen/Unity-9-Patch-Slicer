# Unity 9 Patch Slicing Based on Sprite Borders


## Information
Generates smaller sized png images. In this way, you can decrease app size and memory usage.


## Setup

### Import As Package

You can import packages using Unity Import Package.
You can find versions in Build folder

Note: Use Crunch Compression should be disabled for the source sprite.


## Description

Configure source image sprite borders first

<img src=".res/images/img4.png" width="600" />

Apply slice operation

<img src=".res/images/img3.png" width="600" />

Congrats !! Before And After

<img src=".res/images/img2.png" width="600" />
<img src=".res/images/img1.png" width="600" />

There are two slice operation: with replace feature and without replace. Aware of that if you perform with replace, your original image will be overriden.


Note: If you don't use replace, you may apply the following procedures.

In order to not losing sprite references: 

1- Move newly generated sprite outside of your Unity Project 

2-Remove Old Sprite, make new sprite name same with the removed one. 

3- Import new sprite to the same folder by dragging in Unity Editor.

## Future Releases

I am planning to add new features to this package in the future. 

Original GitHub Pages: https://github.com/kyubuns/Auto9Slicer , https://github.com/pshutov/OnionRing-Unity

## Release Notes

CHANGELOG (see [CHANGELOG](CHANGELOG.MD))

## License

MIT License (see [LICENSE](LICENSE))


