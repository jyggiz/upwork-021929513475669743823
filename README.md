### Problem

The page was initially loading **all \~400 audio files** at once, which caused long loading times.
As a result, when a user clicked the play button, the audio wasn’t ready yet — and nothing happened.

### Solution

I changed the approach by **removing the initial loading** of all \~400 audio elements.
Instead, I kept only **one audio element** that by default loads the **first audio track**.

When a user **hovers** over a track, it immediately starts loading the corresponding audio.
Additionally, when an audio finishes, it **automatically loads the next one**.

This approach allows the page to load much faster and ensures the user only loads the audio they actually need, reducing unnecessary delays.

P.S Solution 1 use absolute path and solution 2 use relative path to load audios.
