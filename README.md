# GeneriKit
Generic patches. Those that were revoked by the sages.

## Usage

Having to patch a file and build a entire kernel is a medium-level of knowledge to the majority of users.<br>
But choosing which file to compile is a hard task. And that is what this repository is for.

## Dependencies

In the middle of the repository jouney, most of the systems will have a automated install.<br>
But this day is most likely to happen very far from now. So, consider having the following:

- git
- gcc
- make
- Linux Headers

The headers are important because it creates a `/lib/modules/KERNEL_VERSION/build` file, which is used to build the modules.

## Building

Building for now is very dirty. But, hey, "if it works, it works!":
```bash
git clone --recursive https://github.com/KanuX-14/GeneriKit.git
cd GeneriKit
make && sudo make install clean
```

## Inspiration

One time this patch got revoked by the zen-kernel programmers.<br>
Just like they said: "I'd really prefer we don't add code for fakes."

Even knowing it is generic, the device continue being a device.

## Contribution

You are more than welcome to submit a driver that got revoked by the team.<br>
If your driver bugs some architecture, consider putting a `warning.txt` file within the directory.

## References

My first [closed pull request](https://github.com/zen-kernel/zen-kernel/pull/279).
