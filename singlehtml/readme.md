trying to make use of simple file, easy delivery (using link: https://html-preview.github.io/?url=https://github.com/wenyaoxue/kdramastats/blob/main/singlehtml/kdramastats.html)
trying to figure out mobile - that's why there's gonna be a ton of commits

7/23 around 21:00 - officially started coderystal! https://github.com/coderystal/kdramastats/blob/main/v1/index.html preview tinyurl: tinyurl.com/kdramastatsv1

note: for mouse down, mouse up, mobile and desktop
```
    span.style.backgroundColor = "black"
    span.onmousedown = () => { span.style.backgroundColor = "floralwhite" }
    span.ontouchstart = () => { span.style.backgroundColor = "floralwhite" }
    span.onmouseup = () => { span.style.backgroundColor = "black" }
    span.ontouchend = () => { span.style.backgroundColor = "black" }
    span.onmouseleave = () => { span.style.backgroundColor = "black" }
```
not
```
doesn't work on mobile:
    .spoiler {
      background-color: black;
    }

    .spoiler:active:hover {
      background-color: floralwhite;
    }
```
figuring out sizing:
as per [this answer](https://stackoverflow.com/a/41668690), body gets a margin by default

note: a lot of embedded videos showing as unavailable on local, but not once published (ie using github preview link)
