# BeatmapStation
BeatmapStation is a tool which downloads beatmaps from osu! by searching for them, by replays, or even by messages sent to the user in-game. More information can be found at the [official thread](https://osu.ppy.sh/community/forums/topics/727561)

For the moment, this is going to stay just as a simple repository to make the translation easier for those who want to contribute to this matter. Also, it'll be used to track issues on the app.

### Some translating guidelines
1. Before making a pull request, please find your language on [Java's supported locales](https://www.oracle.com/technetwork/java/javase/java8locales-2095355.html#util-text) and use the language tag as your filename (use an underline instead of a dash, i.e: `en-US` -> `en_US`).

   1. Also, you're advised to use just the language code (the first part of the tag) if your language has multiple variations and they're understandable on the most countries where they're spoken. For instance,  `es_AR`, `es_BO`, `es_CL` would be just `es`.

1. Please use only UTF-8 as your file's character encoding if possible. But if by chance you send in another encoding, I'll fix it, so don't worry much about it.

1. The **Profile ID** is your user ID on the osu! site. It's used to link your profile on the settings screen if people wanna see who translated the language they're using.
If you don't know what's yours, just enter in your profile on the new site and you'll be redirected to the URL containing your ID (for example: https://osu.ppy.sh/users/Eber -> https://osu.ppy.sh/users/6394801)

1. Don't worry about the `merge.timestamp` field. It's used in the language updating system on the client and I'll be putting a new one everytime a language file is added or updated.
