# Wine packages

* `wine-ge` is the wine equivalent of the famous Proton-GE. It is based on
`wine-tkg`, and is expected to work better than it.

* `wine-osu` is wine-staging, with patches applied to make it low-latency.
The patches can be found
[here](https://drive.google.com/drive/folders/17MVlyXixv7uS3JW4B-H8oS4qgLn7eBw5).

* `wine-tkg` is a special wine version, tailored for the best gaming experience.
It consists of a wine tree generated with
[the tkg patches](https://github.com/Frogging-Family/wine-tkg-git).

* `wine-ge-rekordbox` is `wine-ge` built with patches fixing https://bugs.winehq.org/show_bug.cgi?id=56735
to enable USB export in rekordbox by @jpf91. The release can be found
[here](https://github.com/jpf91/proton-wine/releases/tag/rekordbox_1)