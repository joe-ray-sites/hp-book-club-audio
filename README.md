# Harry Potter Book Club — chapter audio

The club's homemade audiobook recordings, one MP3 per chapter, in `book<N>/book<N>-ch<NN>.mp3`
(Book 7's epilogue is `book7/book7-epilogue.mp3`). They are streamed by the Listen tab of
https://joe-ray-sites.github.io/hp-book-club/ straight from `raw.githubusercontent.com`, which
serves plain files with HTTP Range support and no redirect (Google Drive and GitHub release
assets both fail in mobile browsers — see the app repo's CLAUDE.md, gotchas 11–12).

The catalogue of record is `tools/listen.py` in the app repo; `tools/audio-repo.py` there lays
this tree out from the owner's local copy and verifies every URL. Do not rename files or folders:
the app derives each URL from the book and chapter number.
