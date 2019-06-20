# ytsub.mnh48.moe
The website containing all source files of translations made by
The MNH48 Channel for various YouTubers.

## What this repository contains?
This repository includes the backups of old recovered Malay
translation files for various YouTubers, and the website files
detailing each of the channels with the translations. Current
and future translations will also be added to the repository
and the list on the website.

## What kind of translations?
There are two type of contents that is translatable:
- Video descriptions
- Video subtitles

### Video descriptions
The video descriptions are saved as the original video title,
followed by a period, language code, a period, and finally `txt`.

For example: `Kizuna AI - Hello, Morning (Prod.Nor).ms.txt`

All the descriptions on the website and in the repository are
translation files submitted to the YouTubers, however there
might be further edit by others, so it might not be the same as
the latest translation on the video itself. Also note that some
videos still didn't publish the translated descriptions, I can't
do anything about that from my end.

### Video subtitles
The video subtitles are saved as the original video title,
followed by a period, language code, a period, and finally the
extension of the subtitle format used.

For example: `Kizuna AI - Hello, Morning (Prod.Nor).ms.sbv`

Almost all of the older videos has had subtitles edited directly
in YouTube's web interface, and I just save the final edit before
submitting it to the system. These files were saved as SubViewer
caption files with the extension `.sbv`.

Some of the videos has had the subtitles edited in Aegisub, but
saved in the most basic format of SubRip Text due to YouTube not
accepting most of other formats that could be exported from
Aegisub. These files use the extension `.srt`.

Current and future videos will have subtitles edited in Aegisub,
with both the original stylized native file and the converted
file kept together. The original stylized native files are
Advanced SubStation Alpha with the extension `.ass` whereas the
converted files are YouTube Timed Text with the extension `.ytt`.
The conversion uses the [YTSubConverter](https://github.com/arcusmaximus/YTSubConverter)
tool created by arcusmaximus on GitHub.

Do note that all these only applies to the subtitles for YouTube
translations. Translation subtitle hosted directly on my websites
are Web Video Text Track (WebVTT) with the extension `.vtt`.

## Languages of translations
I only do Malay translations, because I don't have the time to
do translations in other languages. However, do note that I
understand and use the following languages in my daily life:
- Malay (my native language)
  - Standard Malay (bahasa Melayu piawai): the lingua franca in Malaysia
  - Formal Malaysian (bahasa Melayu baku): the official language of Malaysia
  - Informal Malay (bahasa pasar): the daily casual spoken variant of Malay language
  - Kedah Malay (loghat utagha): the Kedah and northern Malaysia dialect of Malay language
  - Malaysian pidgin (bahasa rojak): the code-switching of two or more languages of Malaysia
  - Writing and reading capability: both Rumi (Latin) and Jawi (Arabic) scripts
- Chinese (my second language since kindergarten)
  - Malaysian Mandarin: the standard Mandarin for Chinese schools in Malaysia
  - Informal Kedah Chinese pidgin: the daily casual spoken variant of Chinese language in Kedah and northern Malaysia, involves code-switching between Mandarin, Kedah Hokkien and Malaysian Cantonese.
  - Writing and reading capability: both traditional (繁體字) and simplified (简体字) Chinese characters
- English (my third language since primary school)
  - Malaysian English: the standard English taught in schools nationwide (which follows UK English, with addition of local English words)
  - Informal English: the daily casual spoken variant of Malaysian English
  - Malaysian Mixed English Writing: The choice of words commonly used when writing English in Malaysia is a mixed of local, US, and UK variants of English, surprisingly it is understandable by all Malaysians. This is different from the standard Malaysian English writing. General rules of thumbs are:
    - Use -our form: colour, flavour (UK English)
    - Use -ze form: stabilize, analyze (US English)
    - Use -se form: license, practise (US English)
    - Mixed use of -re and -er form: fibre, meter (mixed of US and UK English)
    - Use e- form: estrogen, anesthesia (US English)
    - Use -gue form: prologue, analogue (UK English)
    - Use the t past tense: learnt, burnt (UK English)
    - Use Malay particles at the end of English sentences: -lah, -kah (local English)
    - Use Malay loanwords in English sentences: Perdana Menteri, Agong (local English)
- Japanese (my fourth language since secondary school (informally) or university (formally))
  - I started self-learning Japanese in secondary school, mostly following Japanese guidebooks written in Chinese, before taking formal Japanese class that uses mix of Malay and English in my university.
  - I can also read some of the deprecated kana like WI (ゐ) and WE (ゑ) among others.
  - I have my own romanization system when I include Japanese lyrics in Malay subtitles, read more about it [here](https://home.mnh48.moe/perumian_en).
    - The romanization is based on Malay instead of English (eg. particle を is always an WO as that's what it sounds like in Malay, even if it sounds like an O in English.)
    - It's only used in Malay subtitles, if I ever make English subtitles I'll use Hepburn romanization system instead.

## Copyrights
Since the subtitles are translations of what is being spoken in
the video, which is ultimately a derivative of copyrighted
material, the subtitles are also copyrighted the same way as
the original video's copyright. You can download the subtitles
(and in fact I provide them for download) but please keep it to
personal-use only. I retain the copyright of the translations,
but I do not own the original text, those were owned by the
author of the videos.
