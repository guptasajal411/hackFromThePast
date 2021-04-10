# hackFromThePast-MLH
A site with favourite video game memories from your childhood! Made with HTML and CSS.
Now you can add your treasured games to the site too!

You can see the website [**here.**](http://guptasajal411.github.io/hackFromThePast-MLH/)

This website is best viewed on desktops. Not optimized for mobile view. 

## Contributing Guide
* * *
If you want to add your own game to the site, follow these steps:

1. Fork the project repository.
2. Clone the forked repository on your machine.
3. Add your photo inside the `images` folder. Make sure to rename it as name of the video game.
4. Add your game inside the `index.html` and `styles.css` file as follows:
```
        <div class="NAME OF YOUR GAME">
            <div class="container">
                <div class="row">
                    <div class="col-4">
                        <h1 class="brandNameContainer">NAME OF THE VIDEO GAME</h1>
                        <p class="brandTagline">TAGLINE OF THE GAME</p>
                    </div>
                    <div class="col-8">
                    </div>
                </div>
            </div>
        </div>
```

In styles.css,
```
.NAME OF YOUR GAMW{
    padding-top: 10%;
    padding-bottom: 25%;
    background-image: url("images/NAME OF YOUR GAME.png");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
}
```

5. Make changes by adding your information wherever mentioned.
6. That's it! Stage your changes (`git add -A`)
7. Commit your changes (`git commit -m "Add favorite game to the site"`)
8. Push to the changes to your forked repo (`git push origin master`)
9. Open a pull request and I will merge your contribution to the repo!

* * *
