# How to edit "Dear Us"

**All website text is in one file: `src/data/content.ts`.**

## Change a heading or button

Open `src/data/content.ts`, find the sentence, and change only the words inside the quotes `"..."`. Keep the commas.

## Add a personalized letter

In `personalLetters`, copy one line like:

```
{ name: "Sample A", title: "for the brave one", envelope: "blush", message: "..." },
```

paste it below, then change `name` and `message`. Delete a line to remove a letter. Names match regardless of capitals or Vietnamese accents.

> Privacy: these letters live in the website code, so a curious person could read them. For truly private letters, ask Lovable to move them to secure server storage with access control.

## Replace a photograph

Upload the image into `public/photos/` (e.g. `dalat.jpg`), then in `memories` set `photo: "/photos/dalat.jpg"`. Empty `photo: ""` shows a flower.

## Add music

Upload an mp3 to `public/music/our-song.mp3`, or change `music.src` to your file's path. Music stays off until the visitor taps the button.

## Preview and publish

Changes appear in the Lovable preview automatically. Click **Publish** (top right) to put them live.
