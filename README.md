# cul-de-sac

## roadmap

- ~~search youtube api~~
- ~~start into fullscreen~~
- limit search results to 50 views
- add user controls during playback
- query again on end of video or on next key
- add relationship to next queries
    - generic list loop
    - current video keywords
    - deep learning from queries
- enhance website design

## controls

        [esc]   exit fullscreen (TODO during playback)

## setup

1. create api key

    https://support.google.com/googleapi/answer/6158862?hl=en

2. enable youtube api

    https://console.developers.google.com/apis/enabled

### localhost

1. run a server to deliver this page

        python -m http.server 8000 --bind 127.0.0.1

    reason: https://github.com/google/google-api-javascript-client/issues/46

2. open the page in your browser

    http://127.0.0.1:8000/

### gh-pages

1. go to the project page

    https://digitalburqa.github.io/cul-de-sac/

## authors

- vanessa sioufi
- vsevolod ivanov
