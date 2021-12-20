This project was created following the video from Benjamin Code.

I wanted to learn how the animation was created.

This is the part in the video where the magic happens:
https://youtu.be/JTG6VoLJuAc?t=422

I used `display: flex` instead of using `display: grid` as shown in the video.

```
.right {
    display: flex;
    gap: 4rem;
    flex-grow: 1;
    justify-content: space-between;

    .item {
        flex: 1;
        background-position: center top;
        background-size: auto 100%;
        border-radius: 2rem;
        background-repeat: no-repeat;
        transition: all 0.5s ease;

        &:hover {
            flex: 1.75 0 0;
            background-size: auto 120%;
        }
    }
}
```
