![Ironhack](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_6e171edc323b4df30ae1f1cefe63c7e2.png)

HTML & CSS
====================================

**Images to download**

- [Background](https://github.com/Mi6u3l/Ironhack_Spotify/blob/master/images/background.jpg)
- [Icon-devices](https://github.com/Mi6u3l/Ironhack_Spotify/blob/master/images/icon-devices.png)
- [Icon-sound](https://github.com/Mi6u3l/Ironhack_Spotify/blob/master/images/icon-sound.png)
- [Icon-waveform](https://github.com/Mi6u3l/Ironhack_Spotify/blob/master/images/icon-waveform.png)
- [Spotify-logo](https://github.com/Mi6u3l/Ironhack_Spotify/blob/master/images/spotify-logo.png)



HTML Part 1
-----------------------------
```
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Spotify</title>
  </head>
  <body>
    Hello there!!!
  </body>
</html>
```


HTML Part 2
-----------------------------
```
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Spotify</title>
  </head>
  <body>
    <header>
      <img src="./images/spotify-logo.png" />
      <nav>
        <a href="#0">Premium</a>
        <a href="#0">Discover</a>
        <a href="#0">Help</a>
        <a href="#0">Download</a>
      </nav>
    </header>

    <section>
      <div>
        <h1>Music for everyone.</h1>
        <p>
          Spotify is now free on mobile, tablet an computer. <br />
          Listen to the right music, wherever you are.
        </p>
      </div>
    </section> 

  </body>
</html>
```


HTML Part 3
-----------------------------

```
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Spotify</title>
  </head>
  <body>
    <header>
      <img src="./images/spotify-logo.png" />

      <nav>
        <a href="#0">Premium</a>
        <a href="#0">Discover</a>
        <a href="#0">Help</a>
        <a href="#0">Download</a>
      </nav>
    </header>

    <section>
      <div>
        <h1>Music for everyone.</h1>
        <p>
          Spotify is now free on mobile, tablet and computer. <br />
          Listen to the right music, wherever you are.
        </p>
      </div>
    </section>

    <footer>
      <h2>What's on Spotify?</h2>
      <ul>
        <li>
          <img src="./images/icon-sound.png" />
          <h3>Millions of Songs</h3>
          <p>There are millions of songs on Spotify.</p>
        </li>

        <li>
          <img src="./images/icon-waveform.png" />
          <h3>HD Music</h3>
          <p>Listen to music as if you were listening live.</p>
        </li>

        <li>
          <img src="./images/icon-devices.png" />
          <h3>Stream Everywhere</h3>
          <p>Stream music on your smartphone, tablet, or computer.</p>
        </li>
      </ul>
    </footer>
  </body>
</html>
```

CSS Part 1
-----------------------------
```
<link rel="stylesheet" href="./css/style.css" />
```

```
body {
  font-family: 'Open Sans', sans-serif;
  font-weight: lighter;
  margin: 0;
}

header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  height: 100px;
  padding-left: 3%;
  padding-right: 3%;
  font-size: 25px;
}

header img {
  height: 75%;
}

header a {
  margin-left: 25px;
  color: black;
  text-decoration: none;
}


h2 {
  font-size: 35px;
  text-decoration: underline;
  text-underline-position: under;
}


h3 {
  font-size: 30px;
}


ul {
  padding: 0;
  list-style: none;
}
```

  
CSS Part 2
-----------------------------
```
<section class="big-section">
```

```
.big-section {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-image: url(../images/background.jpg);
  background-size: cover;
  background-position: bottom;
  height: 768px;
  color: white;
}

.big-section h1 {
  font-size: 80px;
  margin-top: 0;
  margin-bottom: 40px;
}

.big-section p {
  font-size: 30px;
}
```


CSS Part 3
-----------------------------
```
<footer class="features">
```

```
.features {
  text-align: center;
}

.features h2 {
  text-decoration-color: #00c76f;
}

.features h3 {
  margin-top: 0;
  color: #00c76f;
}

.features ul {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-top: 7%;
  margin-bottom: 7%;
}

.features li {
  width: 20%;
}

.features p {
  font-size: 25px;
}

.features img {
  width: 50%;
}

```

Want to learn more?
-------------------

Here are some extra resources to learn more about HTML & CSS.

- [CSS-Tricks](https://css-tricks.com/) - In-depth guides on all things CSS.
- [Flexbox playground](https://codepen.io/enxaneta/full/adLPwv) - An interactive page to learn about what all the Flexbox properties do.
- [Flexbox Froggy](https://flexboxfroggy.com/) - A cool game to learn more about Flexbox.
- [CSS Grid course](https://cssgrid.io/) - Free videos to learn about CSS Grid (the next generation flexbox).
- [Bootstrap 4 Video](https://youtu.be/9cKsq14Kfsw) - A video to learn about Bootstrap, a cool tool to write less CSS.

Of course, to get better you need to continue to build Websites!
