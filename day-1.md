# Daily learning
## Morning Planning
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">

### To-do
- item 1
- item 2
- item 3
* item 4
* item 5
1. item 6
2. item 7
- [ ] done
- [x] not done
