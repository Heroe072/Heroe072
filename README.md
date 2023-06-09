
<!---Title: `The video returned by YouTube isn't the requested one. (WEB client) (VideoNotAvailableException)`
Date: `2023-06-09T17:20:44Z`
Route: `/watch?v=vQfyQqo1644`
Version: `2023.06.04-c8b7bf2 @ master`

<details>
<summary>Backtrace</summary>
<p>
   
```
The video returned by YouTube isn't the requested one. (WEB client) (VideoNotAvailableException)
  from /usr/lib/crystal/core/json/any.cr:102:10 in 'extract_video_info:video_id'
  from /usr/lib/crystal/core/hash.cr:1185:13 in 'fetch_video'
  from src/invidious/videos.cr:365:13 in 'get_video:region'
  from src/invidious/routes/watch.cr:63:15 in 'handle'
  from lib/kemal/src/kemal/route.cr:13:9 in '->'
  from lib/kemal/src/kemal/config.cr:92:7 in 'call'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call_next'
  from lib/kemal/src/kemal/filter_handler.cr:21:7 in 'call'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call_next'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call_next'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call_next'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call_next'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call_next'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call'
  from /usr/lib/crystal/core/http/server/handler.cr:28:7 in 'call_next'
  from lib/kemal/src/kemal/init_handler.cr:12:7 in 'process'
  from /usr/lib/crystal/core/http/server.cr:500:5 in '->'
  from /usr/lib/crystal/core/fiber.cr:146:11 in 'run'
  from /src/boringssl/src/google-boringssl-251b516/ssl/internal.h:334:8 in '??'
```
</p>
</details>
Heroe072/Heroe072 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
