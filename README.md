[![CircleCI](https://circleci.com/gh/oparaskos/UMA.svg?style=svg)](https://circleci.com/gh/oparaskos/UMA)


## ![UMA](logo.png)

Unity Multipurpose Avatar System, or UMA for short, is a free character creation and modification system with lots of cool features. UMA was designed with flexibility in mind, so although it's primary purpose is for working with humanoid characters, its systems can be adapted to work with any model you like. So if you want to create modifiable, optimised models for use in your games. UMA is the place to start. As a community project UMA is always being improved. Although the best efforts are made to keep this wiki up to date, it relies on the spare time of helpful individuals to maintain. If you want more help or feel like chipping in then get involved with one of the community links below.


Git repo: https://github.com/umasteeringgroup/UMA

Wiki:     http://umadocs.secretanorak.com/doku.php?id=start

Forum:    http://forum.unity3d.com/threads/uma-unity-multipurpose-avatar-on-the-asset-store.219175

License:  MIT

[![UMA Intro](intro.png)](https://youtu.be/qzJeMWNEhWM)]


## Install
### Using Git

Make sure the Git client is installed on your marchine and that you have added the Git executable path to your `PATH` environment variable.

Navigate to `%ProjectFolder%/Packages/` and open the `manifest.json` file.

in the "dependencies" section add:

```json
{
  "dependencies": {
      ...
      "com.secretanorak.uma":"https://github.com/oparaskos/com.github.umasteeringgroup.uma.uma.git"
      ...
  }
}
```

Find more information about this [here](https://docs.unity3d.com/Manual/upm-git.html).
