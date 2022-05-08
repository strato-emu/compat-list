### [Skyline's](https://github.com/skyline-emu/skyline) Compatibility List
A repository with [**GitHub Issues**](https://github.com/skyline-emu/skyline-games-list/issues) of Switch titles and their corresponding compatibility status with <a href="https://github.com/skyline-emu/skyline"><b>Skyline</b></a>, reporting regressions and progression in a title's status (`nothing`, `boots`, `ingame` or `playable`) alongside tagging them with metadata for efficient retesting and tracking what the most pertinent issues may be for focusing development efforts.

#### How do I contribute?
You can start contributing by checking if any title you want to test already has a [**issue**](https://github.com/skyline-emu/skyline-games-list/issues) by using the search feature: 
* **If you can find one**: You can comment on the existing issue given what you see compatibility differs from the previous report. It is recommend to tag along a Skyline log (with log level `Info`) and clearly describe the differences you're seeing with a brief description of your device. 
* **If you cannot find an existing report**: You can go ahead and [create an issue](https://github.com/skyline-emu/skyline-games-list/issues/new?assignees=&labels=triage&template=bug_report.yaml&title=%3CFull+game+name+displayed+in+skyline%3E) for it by filling all the details in the form.

#### Should I include a image/video of Skyline?
As a general guideline, media should be included when it is useful to do so and provides information that cannot be conveyed via text, these guidelines serve as a rough idea of why they may be important in certain circumstances and not in others. Additionally, any media captured **must** be a direct screen capture rather than an external recording using another phone or a camera. If it is impossible to do so due to the nature of the bug, this can be ignored but generally it shouldn't be.
* **Crash**: A photo/video is generally useless in the case of a crash as the log *should* contain the crash, it may not in certain cases and we can request them in a further comment and in those cases the guidelines of a **Freeze** can be utilized.
* **Freeze**: A video is generally useful to fully understand what the bug is and in this case it should be included, it is important to have the **Show Performance Statistics** enabled in this case as it helps us determine the exact point of the freeze.
* **Auditory Glitch**: A video is useful when there are random dropouts in audio or if it doesn't sound correct, an exception is when the game is not playing any audio at all in which case there is no need to upload a image/video.
* **Visual Bug/Glitch**: At minimum, a photo is required here when the glitching is persistent. A video is useful if the glitch is very visually diverse or pops in occassionally rather than being persistent.

#### I can't upload a Skyline Log (`.sklog`) to GitHub?
GitHub only allows uploading files with a subset of extensions, it is recommended to rename the extension to `.txt` or zip the log and then upload it. If the zipped file cannot be uploaded due to being too large as a last resort you can use an external file hoster such as [Google Drive](https://drive.google.com/) or [Mega](https://mega.nz/) (Decryption key **must** be included in the URL).
