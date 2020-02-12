## Script to call in MFL

<script src="https://brickyt.github.io/playerBadgeScript/index.js"></script>

## Adding new club with image and tooltip image

 - Let the club name be `AAA`

 - Let the image to be displayed beside the player name in club `AAA` be `playerclub.png`
 - Convert this image to `base64` string using sites like https://www.base64-image.de . This will generate `base64` string for `playerclub.png` let us call it `playerclubBase64`

 - Let the image to be displayed when mouseover or clicked on  the image beside the player name be 'playerclubdetails.png'
 - Convert this image to `base64` string using sites like https://www.base64-image.de . This will generate `base64` string for `playerclub.png` let us call it `playerclubdetailsBase64`

 - Open the `index.js` file to add the new details

# 1
Update `cMap` to point to the name
```
    cMap = {
            "AAA" : "PLAYERCLUB"  //notice that playerclub is now in caps

    }

```
# 2
Update the `images` to point the `playerclub` to the base64 representation
```
images = {
    "playerclub" : "playerclubBase64" //value gotten from https://www.base64-image.de  page

}

```

# 3
Update the `tips` to point the `playerclubdetailsBase64` to the base64 representation
```
images = {
    "playerclub" : "playerclubdetailsBase64" //value gotten from https://www.base64-image.de  page

}

```

That's it!


