FoZoWo shared-language architecture

Files:
- index.html       1 home page (all 10 languages)
- character.html  1 character page (all 10 languages)
- header.html     shared external header
- language.js     shared 10-language dictionary + language routing/persistence

Languages: ja, en, hiragana, ko, zh-cn, zh-tw, es, fr, de, pt

Language URLs use one HTML file with ?lang=...:
- index.html?lang=ja
- index.html?lang=en
- character.html?lang=en

The selected language is saved in localStorage under FoZoWo-language and also reflected in the URL.
Navigation between home and character keeps the selected language.

This package intentionally does not include index.html or the duplicated per-language HTML pages.
Keep the existing image/audio files in the same site folders as before.
