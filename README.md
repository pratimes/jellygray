# jellygray
A clean jellyfin skin with joy of gray.

## Installation
1. Go to Settings -> Display -> 
  - `Theme: Dark`
  - `Server Dashboard theme: Dark`
  - `Backdrops: check`
  - `Details Banner: uncheck`
2. Add below line in `Custom CSS code`
```css
@import url('https://pratimes.github.io/jellygray/theme.css');
```

## To enable fanart/logo
- Install the Fanart plugin first
- Go to Dashboard > Library
- For each library you have, go to Manage Library
- Enable Fanart for image fetcher
- Then go to Fetcher Settings and select "Logo"
- Manually scan media library
- Refresh the page once done

## Nginx
If you are using nginx as a reverse proxy for Jellyfin, replace the "add_header Content-Security-Policy" in your nginx config with this line below
```
add_header Content-Security-Policy "default-src https: data: blob: http://image.tmdb.org; style-src 'self' 'unsafe-inline' https://pratimes.github.io ; script-src 'self' 'unsafe-inline' https://www.gstatic.com/cv/js/sender/v1/cast_sender.js https://www.youtube.com blob:; worker-src 'self' blob:; connect-src 'self'; object-src 'none'; frame-ancestors 'self'";
```
## Images
#### Login
![login](https://user-images.githubusercontent.com/108912069/204138261-9817e5c0-eee9-4c54-acfe-062404275f53.png)

#### Homepage
![homepage](https://user-images.githubusercontent.com/108912069/204138258-8e0c6c92-ac4b-4f6b-bbe8-75a531a03469.png)

#### Movie List Page
![moviepage](https://user-images.githubusercontent.com/108912069/204138275-288667e8-4e4f-40c5-a8d8-dc943e95e808.png)


#### Some Movie Pages
![movie](https://user-images.githubusercontent.com/108912069/204138268-6ae4e79c-58a1-4678-9667-eb60e35aaf2b.png)

![movie_item](https://user-images.githubusercontent.com/108912069/204138272-b715b70e-daa5-4de6-a2d9-faf8ea2b30a0.png)

![movie_item2](https://user-images.githubusercontent.com/108912069/204138274-7b2774ed-7945-438a-82ef-60289e0edaf1.png)

#### TV Show Page
![tv-show](https://user-images.githubusercontent.com/108912069/204138287-ad1d3301-7272-403e-9ecd-fcd1eac493dc.png)

#### TV Season Page
![tv-season](https://user-images.githubusercontent.com/108912069/204138285-a01a03af-b321-47f5-81f6-ac1673d4a894.png)

#### TV Episode
![tv-episode](https://user-images.githubusercontent.com/108912069/204138284-84bf6553-3aba-4188-a60b-d87ca6d0f0ca.png)

#### Web Player
![player](https://user-images.githubusercontent.com/108912069/204138278-72a13aef-09a4-44ce-b67f-bb5273b0f9f9.png)

#### Menu
![menu](https://user-images.githubusercontent.com/108912069/204138264-0bb74e22-8255-46ad-8c4f-c528c58ee756.png)

#### Dashboard
![dashboard](https://user-images.githubusercontent.com/108912069/204138257-aeaa197f-67f1-44b1-a9eb-180262b8b47c.png)

#### Plugin
![plugin](https://user-images.githubusercontent.com/108912069/204138282-feee39c0-b879-44e6-86b4-4ed0d0955e76.png)

#### Actor Page
![actor-page](https://user-images.githubusercontent.com/108912069/204138251-a8501ac1-38b5-4952-bbb0-344ac33f4048.png)


## Thanks
This css theme is based on [HintOfGreenCSS](https://github.com/looi-wh/HintOfGreenCSS) by looi-wh and [Ultrachromic](https://github.com/CTalvio/Ultrachromic) by CTalvio.
