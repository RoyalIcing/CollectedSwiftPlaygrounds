# CollectedSwiftPlaygrounds

Swift Playgrounds for interacting with Collected.Press

## WebSocket Client

Connects via a WebSocket to <https://collected.press>, which renders Markdown and is hosted on [Cloudflare Workers](https://workers.cloudflare.com).

You can send various sized pieces of Markdown, and see how long it takes to do a round trip from your computer to the server and back. You can see it in seconds and in number of frames (assuming 60FPS).

In Melbourne, I’m seeing hundreds of a second (~10–50ms), which translates to 1–4 frames @ 60FPS. That’s enough to make it feel near instantaneous, as if it’s not even over the network but as fast as something running on my computer.

<img width="1470" alt="image" src="https://user-images.githubusercontent.com/2635733/169691040-17f70acd-4e6c-45b7-b378-4f87214f1139.png">
