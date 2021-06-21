---
title: Add a video
description: How to add a video into your posts
date:
---
This post will show you how to add a video onto your post.

Example Video:

<figure class="figure_container">
    <video controls="true" allowfullscreen="true" width="100%">
        <source src="/videos/test.mp4" type="video/mp4">
    </video>
</figure>

How to add a video into a post
- Add the video to the videos folder
- Inside the post, add the following:
<pre style="position: relative;">
<span class="hljs-tag">&lt<span class="hljs-name">figure</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"figure_container"</span>&gt</span>
<span class="hljs-tag">&nbsp &lt<span class="hljs-name">video</span> <span class="hljs-attr">controls</span>=<span class="hljs-string">"true"</span> <span class="hljs-attr">allowfullscreen</span>=<span class="hljs-string">"true"</span> <span class="hljs-attr">width</span>=<span class="hljs-string">"100%"</span>&gt</span>
<span class="hljs-tag">&nbsp &nbsp &lt<span class="hljs-name">source</span> <span class="hljs-attr">src</span>=<span class="hljs-string">"/videos/[video_name]"</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"video/mp4"</span>&gt</span>
<span class="hljs-tag">&nbsp &lt&#47<span class="hljs-name">video</span>&gt</span>
<span class="hljs-tag">&lt&#47<span class="hljs-name">figure</span>&gt</span>
</pre>
- Make sure to change [video_name] to name of video file including video extension (i.e .mp4)
- Then re-run using 'npm start' in terminal

