# Commands zinazotumia API — files na endpoints

Tumia `node scripts/check-apis.js` kuzipima zote (HTTP status) kutoka server/PC yenye mtandao.

| Command(s) | File | API / Endpoint | Key |
|---|---|---|---|
| chatbot | `commands/admin/chatbot.js` | https://openrouter.ai/api/v1/chat/completions | — |
| ai, chatgpt, gpt4o, claude, gemini, mistral, copilot, metaai, aiLlama, blackbox, bard, perplexity, venice, o3 | `commands/ai/ai.js` | https://apiskeith2-production-3020.up.railway.app/ai/bard<br>https://apiskeith2-production-3020.up.railway.app/ai/blackbox<br>https://apiskeith2-production-3020.up.railway.app/ai/chatgpt4<br>https://apiskeith2-production-3020.up.railway.app/ai/claudeai<br>https://apiskeith2-production-3020.up.railway.app/ai/copilot<br>https://apiskeith2-production-3020.up.railway.app/ai/gemini<br>… | — |
| (helper) | `commands/aivideo/ephotoVideo.js` | https://api-photooxy.vercel.app/api/ephoto360<br>https://en.ephoto360.com/<br>https://widipe.com/ephoto360 | — |
| introvideo | `commands/aivideo/introvideo.js` | https://en.ephoto360.com/create-digital-glitch-text-effect-online-772.html<br>https://en.ephoto360.com/free-logo-intro-video-maker-online-558.html<br>https://en.ephoto360.com/free-logo-intro-video-maker-online-582.html | — |
| lightningpubg | `commands/aivideo/lightningpubg.js` | https://en.ephoto360.com/create-gaming-logo-pubg-style-online-free-575.html<br>https://en.ephoto360.com/create-pubg-style-glitch-video-avatar-581.html<br>https://en.ephoto360.com/lightning-pubg-video-logo-maker-online-615.html<br>https://en.ephoto360.com/pubg-battlegrounds-logo-maker-online-free-576.html | — |
| lovevideo | `commands/aivideo/lovevideo.js` | https://en.ephoto360.com/create-romantic-luxury-video-wedding-invitations-online-580.html<br>https://en.ephoto360.com/create-sweet-love-video-cards-online-734.html<br>https://en.ephoto360.com/love-hearts-name-generator-353.html<br>https://en.ephoto360.com/write-text-on-love-hearts-261.html | — |
| tigervideo | `commands/aivideo/tigervideo.js` | https://api.ephoto360.com/create-digital-tiger-logo-video-effect-723<br>https://api.textpro.me/create-tiger-video<br>https://en.ephoto360.com/create-digital-tiger-logo-video-effect-723.html<br>https://en.ephoto360.com{…}<br>https://ephoto-api.vercel.app/api/tiger-video | — |
| videogen | `commands/aivideo/videogen.js` | https://api.pexels.com/videos/search | — |
| hneko | `commands/anime/hneko.js` | https://api.princetechn.com/api/anime/hneko | key: prince |
| hwaifu | `commands/anime/hwaifu.js` | https://api.princetechn.com/api/anime/hwaifu | key: prince |
| konachan | `commands/anime/konachan.js` | https://api.princetechn.com/api/anime/konachan | key: prince |
| megumin | `commands/anime/megumin.js` | https://api.princetechn.com/api/anime/megumin | key: prince |
| milf | `commands/anime/milf.js` | https://api.princetechn.com/api/anime/milf | key: prince |
| random | `commands/anime/random.js` | https://api.princetechn.com/api/anime/random | key: prince |
| waifu, neko, loli, shota, husby | `commands/anime/sfw.js` | https://api.shizo.top/sfw/husbando<br>https://api.shizo.top/sfw/loli<br>https://api.shizo.top/sfw/neko<br>https://api.shizo.top/sfw/shota<br>https://api.shizo.top/sfw/waifu | key: shizo |
| (helper) | `commands/ephoto360/ephoto360.js` | https://api.nekolabs.my.id/ephoto/3d-hologram-text<br>https://api.nekolabs.my.id/ephoto/3d-paper-cut-style<br>https://api.nekolabs.my.id/ephoto/bear-logo<br>https://api.nekolabs.my.id/ephoto/royal-text<br>https://api.nekolabs.web.id/ephoto/text-on-wet-glass<br>https://en.ephoto360.com/advanced-glow-effects-74.html<br>… | — |
| fact | `commands/fun/fact.js` | https://api.shizo.top/quote/quotes | key: shizo |
| flirt | `commands/fun/flirt.js` | https://api.shizo.top/quote/flirt | key: shizo |
| memesearch | `commands/fun/memesearch.js` | https://api.shizo.top/tools/meme-search | key: shizo |
| paranoia | `commands/fun/paranoia.js` | https://api.truthordarebot.xyz/v1/paranoia | — |
| pickupline | `commands/fun/pickupline.js` | https://api.jcwyt.com/pickup | — |
| pies | `commands/fun/pies.js` | https://api.shizo.top/pies | key: shizo |
| question | `commands/fun/question.js` | https://opentdb.com/api.php | — |
| quotes | `commands/fun/quote.js` | https://api.shizo.top/quote/quotes | key: shizo |
| wasted | `commands/fun/wasted.js` | https://some-random-api.com/canvas/overlay/wasted | — |
| wyr | `commands/fun/wyr.js` | https://api.truthordarebot.xyz/v1/wyr | — |
| apk | `commands/general/apk.js` | http://ws75.aptoide.com/api/7/apps/search/query=${encodeURIComponent(query | — |
| google, image2, define, news2 | `commands/general/google.js` | https://api.dictionaryapi.dev/api/v2/entries/en/${encodeURIComponent(word<br>https://api.giftedtech.co.ke/api/search/googleimagesearch<br>https://api.giftedtech.co.ke/api/search/googlenews<br>https://api.giftedtech.co.ke/api/search/googlesearch<br>https://api.giftedtech.co.ke/api/search/googlesearch?apikey=gifted&q= | key: gifted |
| img | `commands/general/image.js` | https://api.cod3uchiha.com/downloaders/img<br>https://commons.wikimedia.org/ | — |
| pair | `commands/general/pair.js` | https://pair1.adevosxtech.site/code | — |
| telegramsticker | `commands/general/telegramsticker.js` | https://api.telegram.org/bot{…}/getFile<br>https://api.telegram.org/bot{…}/getStickerSet<br>https://api.telegram.org/file/bot{…}/{…} | — |
| (helper) | `commands/media/adultVideoHelpers.js` | https://api.giftedtech.co.ke/api | key: gifted |
| facebook | `commands/media/facebook.js` | https://apissupreme.vercel.app/media/facebook | key: supreme |
| igs | `commands/media/igs.js` | https://d.rapidcdn.app/v2 | — |
| igsc | `commands/media/igsc.js` | https://d.rapidcdn.app/v2 | — |
| lyrics | `commands/media/lyrics.js` | https://apiskeith2-production-3020.up.railway.app/search/lyrics | — |
| pinterest | `commands/media/pinterest.js` | https://api.nexray.web.id/downloader/pinterest | — |
| AudD, Keith Shazam, Ryzen Shazam, shazam | `commands/media/shazam.js` | https://api.audd.io/<br>https://api.ryzendesu.vip/api/ai/shazam<br>https://apiskeith2-production-ec66.up.railway.app/ai/shazam<br>https://apiskeith2-production-ec66.up.railway.app/download/audio<br>https://yt-dl.officialhectormanuel.workers.dev/ | — |
| snapchat | `commands/media/snapchat.js` | https://api.tiklydown.eu.org/api/download<br>https://api16-normal-c-useast1a.tiktokv.com/aweme/v1/feed/<br>https://musicallydown.com<br>https://musicallydown.com/download<br>https://savetik.co/api/ajaxSearch<br>https://ssstik.io/api<br>… | — |
| soundcloud | `commands/media/soundcloud.js` | https://api.nexray.eu.cc | — |
| spotify | `commands/media/spotify.js` | https://api.nexray.eu.cc/downloader/spotifyplay<br>https://api.nexray.eu.cc/search/spotify | — |
| spotify2 | `commands/media/spotify2.js` | https://api.nexray.eu.cc/downloader/spotifyplay<br>https://api.nexray.eu.cc/search/spotify | — |
| tiktok2 | `commands/media/tiktok.js` | https://www.tikwm.com/api/ | — |
| tt | `commands/media/tt.js` | https://www.tikwm.com/api/ | — |
| twitter | `commands/media/twitter.js` | https://api.hostify.indevs.in | — |
| video2 | `commands/media/video2.js` | https://apissupreme.vercel.app/media/ytmp4 | key: supreme |
| video3 | `commands/media/video3.js` | https://apiskeith2-production-3020.up.railway.app/download/video | — |
| iboxtv, tvdetail, tvsearch, iboxmovies, moviedetail, moviesearch, iboxanime, animedetail, animesearch, dramabox, actor, moviebox, trailer, moviedl | `commands/movies/movie.js` | https://apiskeith2-production-ec66.up.railway.app | — |
| (helper) | `commands/reaction/reactions.js` | https://api.waifu.pics/sfw/{…}<br>https://nekos.best/api/v2/{…} | — |
| bible, biblelist, biblerandom, quran, ayah, quranrandom, gita, gitarandom, gitachapter | `commands/religeon/holybook.js` | https://api.alquran.cloud/v1<br>https://bible-api.com<br>https://vedicscriptures.github.io | — |
| playersearch, kteamsearch, venuesearch, gameevents, fifaupcoming, fifamatches, fifastandings, fifascorers, livescore, livehighlights, epl, bundesliga, euros, laliga, ligue1, seriea, ucl, bet, footballnews | `commands/sports/sports.js` | https://apiskeith2-production-ec66.up.railway.app | — |
| catbox | `commands/tools/catbox.js` | https://catbox.moe/user/api.php | — |
| enhance | `commands/tools/enhance.js` | https://api.shizo.top/ai/enhance<br>https://uguu.se/upload | key: shizo |
| github | `commands/tools/git.js` | https://github.com/adevos-x-tech<br>https://md.adevosxtech.site | — |
| imgbb | `commands/tools/imgbb.js` | https://api.imgbb.com/1/upload | — |
| llama | `commands/tools/llama.js` | https://apiskeith.vercel.app/ai/ilama | — |
| ocr | `commands/tools/ocr.js` | https://staging-ai-image-ocr-266i.frontend.encr.app/api/ocr/process | — |
| shorturl | `commands/tools/shorturl.js` | https://tinyurl.com/api-create.php | — |
| ssdsktp | `commands/tools/ssdesktop.js` | https://snapshot.xwolf.space/api/capture<br>https://{…} | — |
| ssrecord | `commands/tools/ssrecord.js` | https://snapshot.xwolf.space/api/record<br>https://{…} | — |
| uguu | `commands/tools/uguu.js` | https://uguu.se/upload.php | — |
| translate2 | `commands/utility/translate.js` | https://api.dreaded.site/api/translate<br>https://api.mymemory.translated.net/get<br>https://translate.googleapis.com/translate_a/single | — |

**Textmaker (scrape ya en.ephoto360.com, haina key)** — `commands/textmaker/*.js`: 1917, arena, blackpink, devil, fire, glitch, hacker, ice, impressive, leaves, light, matrix, metallic, neon, purple, sand, snow, thunder


## Utils zenye API (`utils/api.js`, `utils/helpers.js`)
- Siputzx: stablediffusion, translate, weather, igdl, tiktok
- Shizo: gpt (key `shizo`) · Keith 3020: `/download/audio`
- Hectormanuel worker: yt audio · Supreme: ytmp4 (key `supreme`)
- GiftedTech stalk* (key `gifted`) · Xwolf stalk github/tiktok
- Laurine tts · eliteprotech ssweb · NVIDIA NIM (`nvapi-…` imewekwa kwenye code) · Pollinations (bila key)
- Wikipedia, zenquotes, meme-api, official-joke-api, tinyurl (bila key)
- helpers.js: catbox, imgbb, file.io, api.bk9.dev, cod3uchiha

## Zinazotumia env/key binafsi
OpenRouter (`chatbot.js`, `utils/juneDb/orap.js`), Pexels (`PEXELS_API_KEY`), ImgBB (`IMGBB_API_KEY`), GitHub (`GITHUB_TOKEN`), OpenWeather (`utility/weather.js`), Telegram bot token (`config.js`).
