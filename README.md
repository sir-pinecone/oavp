<h1><img src="http://phrakture.com/images/github/oavp-icon-updated.png" width="72" height="72" valign="middle"/>Open Audio Visualizers for Processing</h1>

A set of tools to help build interactive audio visualizers with [processing](https://processing.org), written in Java using the Processing java-applet library with the help of Minim, Ani and the Beads project libraries.

# Getting Started / Docs

Check out the full guide and docs available [at the repo's wiki here](https://github.com/nafeu/oavp/wiki). Documentation is a still a huge work-in-progress and I would greatly appreciate if anyone was interested in helping out :)

# Setup and Installation

- Download and install the [`Processing IDE`](https://processing.org/download/)
- Using the Processing IDE, install the following packages:
  - [`Minim`](https://github.com/ddf/Minim) (for realtime audio analysis)
  - [`Ani`](https://github.com/b-g/Ani) (for tweening and smooth animations)
  - [`Beads`](https://github.com/orsjb/beads) (for time/tempo synced rhythmic operations)
  - You may also need to install the [`Processing Video`](https://github.com/processing/processing-video) package.
- Setup your config.json file in `src/data`. An example file is provided to get you started.

## Using Sublime

- Download and follow the instructions to set up [processing-sublime](https://github.com/b-g/processing-sublime)

```
git clone https://github.com/nafeu/oavp.git [PROJECT_NAME]
cd [PROJECT_NAME]
subl .
```

Open the `sketch.pde` file and use the build command to run the sketch.

`CTRL/CMD + BUILD`

## Using Processing (IDE)

```
git clone https://github.com/nafeu/oavp.git [PROJECT_NAME]
```

Open the `sketch.pde` file in Processing and run it.

## Credits

Nafeu Nasir

## License

MIT
