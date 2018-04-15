# Adobe Premiere Pro CC

## Tips

* `~` maximize selected window.
* (??? `Ctrl` + `Alt` + `K`) to open `Keyboard Shortcuts`.
* [In Project] `Ctrl` + `B` to create a new Bin.
* [In Project] `Ctrl` + `DblClk` to open directory in _same_ window.
* [In Project] Use search bins for browsable "saved searches".
* [In Timeline(s)] `+` to zoom in, `-` to zoom out.
* [In Sequence] `Up`/`Down` are to nav to previous/next piece in sequence.

### Proxies

* `Toggle Proxies` (??? `Ctrl` + `Alt` + `P`).

## TODO RESTORE

## Proxy Workflow

Proxy files (PF) are lower res copies of original media.
PF provides flexibility and improves performance.
PFs are automatically associated with full res media (one-click to switch).

* `File` > `Project Settings` > `Ingest Settings`.
* `V` `Ingest` + `Create Proxies`.
* `Proxy Destination` `Creative Cloud Files` or another location.
* ---
* `Preferences` > `Media`
* `V` `Enable Proxies`
* ---
* Now when media is being imported, Adobe Media Encoder will automatically create proxies.

Otherwise, on a file level:
`RghtClk` > `Proxies` > `Create Proxies...` or `Attach Proxies...` or `Reconnect Full Res...`

## Basic Editing

### Navigation, _in_ and _out_ marks

* [In Source]
  * `j` to previous.
  * `k` to stop/resume.
  * `l` to next.
  * `k` + `j` -- slower back.
  * `k` + `l` -- slower forward.
  * 2, 3, 4 hits on `j` and `l` increase back or forward speed.
  * `i` to mark _in_.
  * `o` to mark _out_.
  * `ctrl` + `shift` + `space` to play from in to out mark.
  * `ctrl` + `space` to play from current location to out mark.
  * `Settings` > `Audio Waveform` is handy.

* [In Project]
  * Mark _in_ and _out_ points while scrubbing (click first).

### Subclips

* [In Source]
  * `Ctrl` + `U` to create a subclip.

### Insert Edit

* [In Source]
  * `,` inserts source into end of sequence (called "splice").
  * `.` inserts source into the sequence with replacement ("overwrite").

* [In Sequence]
  * `End` to go to end of sequence.
  * `\` zoom to sequence.

  * [???????] `End` + `Enter` to play to end of sequence.

### Moving clips; Swapping shots

* [In Sequence]
  * `a` to Track Select Forward.
  * `shift` + `a` to Track Select Backward.
  * `s` to toggle Snapping.
  * `v` to enable Selection Tool.
  * `ctrl` + `alt` + drag clip(s) to swap selected clip(s) with a target one.
  * `alt` + left/right (???? OR `ctrl` + left/right) to nudge (tiny push) selected clip(s). Works with (+ `shift`) too.

### Removing material

* [In Sequence]
  * `c` to enable Razor Tool.
  * `del` to lift (delete with leaving a gap) selected clip(s).
  * `alt` + `del` to extract (delete without leaving a gap) selected clip(s).
  * for a marked section (with `i` and `o`):
    * `;` to lift.
    * `\`` to extract.
  *  `RghtClk` on empty segment > `Ripple Delete`.
    * or `B` and drag with snipping.
