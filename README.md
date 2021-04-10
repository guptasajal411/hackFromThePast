# hackFromThePast-MLH
A site with favourite video game memories from your childhood! Made with HTML and CSS.
Now you can add your treasured games to the site too!

##Contributing Guide
 
If you want to add your own game to the site, follow these steps:

1. Fork the project repository.
2. Clone the forked repository on your machine.
3. Add your photo inside the `images` folder. Make sure to rename it as name of the video game.
4. Add your game inside the `index.html` file as follows:
```
        <div class="teenageMutantNinjaTurtles">
            <div class="container">
                <div class="row">
                    <div class="col-4">
                        <h1 class="brandNameContainer">NAME OF THE VIDEO GAME</h1>
                        <p style="text-align: center;" class="brandTagline">TAGLINE OF THE GAME</p>
                    </div>
                    <div class="col-8">
                    </div>
                </div>
            </div>
        </div>
```
5. Make changes by adding your information wherever mentioned.
6. That's it! Stage your changes (`git add .`)
7. Commit your changes (`git commit -m 'Added my card'`)
8. Push to the changes to your forked repo (`git push origin master`)
9. Open a pull request to get your changes merged to this original repo!
