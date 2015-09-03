# HTML5 Deck of Cards
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/pakastin/deck-of-cards?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Pure vanilla JS – no dependencies.

http://deck-of-cards.js.org

## where's what?

[css/](https://github.com/pakastin/deck-of-cards/tree/master/css) - CSS source (stylus + nib) of the example

[dist/](https://github.com/pakastin/deck-of-cards/tree/master/dist) - deck.js & deck.min.js

[example/](https://github.com/pakastin/deck-of-cards/tree/master/example) - http://deck-of-cards.js.org

[lib/](https://github.com/pakastin/deck-of-cards/tree/master/lib) - JS (ES6) source of deck.js

[views/](https://github.com/pakastin/deck-of-cards/tree/master/views) - HTML source of the example

## build instructions

    npm install
    npm start

(starts watching for changes..)

## Note to self: todo

- Make z-index temporary by reordering DOM elements between actions
- Fix moving
- Make API more open
- Make cards flippable
- Maybe use translate3d for even better performance, but make that temporary because of the smoothing issue
