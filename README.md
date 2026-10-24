# Atsumaru Personal for Mangayomi

Personal Atsumaru extension for itzjustzack, using https://atsu.moe.

[Add to Mangayomi](https://intradeus.github.io/http-protocol-redirector?r=mangayomi://add-repo?repo_name=Atsumaru%20Personal%26repo_url=https://github.com/itzjustzack/mangayomi-atsumaru%26manga_url=https://raw.githubusercontent.com/itzjustzack/mangayomi-atsumaru/main/index.json)

Open the link on your device with Mangayomi installed, add the repository, then install **Atsumaru Personal** under manga extensions.

Manual catalogue URL:
```
https://raw.githubusercontent.com/itzjustzack/mangayomi-atsumaru/main/index.json
```

## Version 0.0.1

- Independent source ID: 3971268045.
- Popular, latest, search, filters, manga details, chapters, and reader support inherited from Swakshan's Atsumaru 0.0.2.
- Dates accept Unix seconds, Unix milliseconds, and ISO timestamps.
- Manga and chapter URLs ignore query strings and fragments.
- Empty reader results show an explicit availability error.

This source has a different ID from other Atsumaru extensions. Existing library entries will not automatically move to it.

## Validation

JavaScript syntax and a simulated Mangayomi client pass checks for catalogue consistency, dates, URLs, browse/search, manga details, chapter sorting, scanlators, and reader output. These checks use sample responses, not the live API.

Live API checks could not complete because atsu.moe could not be reached from the build session. Installation and reading in Mangayomi remain unverified. Restore to your dev environment before app testing.

## Credits

Derived from [Swakshan's Atsumaru extension](https://github.com/Swakshan/mangayomi-swak-extensions/blob/main/javascript/manga/src/en/atsumaru.js), version 0.0.2, under Apache-2.0. See LICENSE and NOTICE.


