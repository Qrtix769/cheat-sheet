# Video

Adding reference of videos to the Markdown file.


## Using Markdown Code

```Markdown

[![<Text>](<link to video's image> "<text to show when the coursor is over the video>")](<link to video> "<text to show when the coursor is over the video>")

```

### Add *YouTube* Video

Below is an example of how to reference a *YouTube* video.

##### Code:
```
[![See the next video](https://img.youtube.com/vi/1BzzckYqT9w/maxresdefault.jpg)](https://www.youtube.com/watch?v=1BzzckYqT9w "How to add reference to YouTube video")
```

##### Rendered output:

[![See the next video](https://img.youtube.com/vi/1BzzckYqT9w/maxresdefault.jpg)](https://www.youtube.com/watch?v=1BzzckYqT9w "How to add reference to YouTube video")
To change the size of the displayed YouTube clickbait you only need to use one of the following names:
- maxresdefault.jpg
- hqdefault.jpg
- default.jpg

## Using HTML Code

Another way to reference videos is by using the HTML `<video>` tag.

```HTML

<video width="320" height="240" controls>

	<source src="https://www.youtube.com/watch?v=1BzzckYqT9w" type="video/mp4">

</video>

```

Can also use the optional attributes shown in the following table to modify the behavior and other characteristics of the video.

### Optional Attributes

<table class="ws-table-all notranslate">
  <tbody><tr>
    <th style="width:20%">Attribute</th>
    <th style="width:20%">Value</th>
    <th style="width:50%">Description</th>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_autoplay.asp">autoplay</a></td>
    <td>autoplay</td>
    <td>Specifies that the video will start playing as soon as it is ready</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_controls.asp">controls</a></td>
    <td>controls</td>
    <td>Specifies that video controls should be displayed (such as a play/pause button etc).</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_height.asp">height</a></td>
    <td><i>pixels</i></td>
    <td>Sets the height of the video player</td>
      </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_loop.asp">loop</a></td>
    <td>loop</td>
    <td>Specifies that the video will start over again, every time it is finished</td>
  </tr>
    <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_muted.asp">muted</a></td>
    <td>muted</td>
    <td>Specifies that the audio output of the video should be muted</td>
  </tr>
    <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_poster.asp">poster</a></td>
    <td><em>URL</em></td>
    <td>Specifies an image to be shown while the video is downloading, or until the user hits the play button</td>
    </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_preload.asp">preload</a></td>
    <td>auto<br>
 metadata<br>
 none</td>
    <td>Specifies if and how the author thinks the video should be loaded when the page loads</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_src.asp">src</a></td>
    <td><i>URL</i></td>
    <td>Specifies the URL of the video file</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/att_video_width.asp">width</a></td>
    <td><i>pixels</i></td>
    <td>Sets the width of the video player</td>
  </tr>
</tbody></table>

