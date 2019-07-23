# PoseNet [[source](https://github.com/tensorflow/tfjs-models/tree/master/posenet)]

## Contents

### Demo: Camera [[source](https://github.com/tensorflow/tfjs-models/tree/master/posenet)]

The camera demo shows how to estimate poses in real-time from a webcam video stream.

<img src="https://github.com/hany606/tfjs-posenet/blob/master/posenet/camera.gif" alt="cameraDemo" style="width: 600px;"/>

## Dependencies
- Install Nodejs from [here](https://nodejs.org/en/download/). For [Ubuntu installation](https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/)
- Install Yarn package manager from [here](https://yarnpkg.com/lang/en/docs/install/). [Usual problem](https://github.com/yarnpkg/yarn/issues/3189) while installing and using yarn with Ubuntu.

and you are ready to go.


## Setup

- cd into the posenet folder:

```sh
cd posenet/
```

- Install dependencies and prepare the build directory:

```sh
yarn --watch
```

- Start the server without websocket server:
```sh
yarn normal
```
- Start the server with websocket server running already:
```sh
yarn websocket
```
Open from the browser http://localhost:1234 to see the running server that estimate the human pose with 17 key points and using websockets to send the data in JSON serialization to a connected websocket server in the network.

The reason behind the exsitance of websocket communication that this project was part of [this](https://github.com/hany606/COEX-Internship19/tree/master/projects/Human_pose_estimation_drone_control); to control a clever 4 drone from Copter Express comapny using Human poses.


## References:
- [Human pose estimation guide](https://blog.nanonets.com/human-pose-estimation-2d-guide/)
- [Clever drones tutorials](https://clever.copterexpress.com/en/)
- [Posenet Github repo](https://github.com/tensorflow/tfjs-models/tree/master/posenet)
- [Posenet meduim article](https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5)
- [Tensorflow.js demos](https://www.tensorflow.org/js/demos)
- [Posenet overview](https://www.tensorflow.org/lite/models/pose_estimation/overview)
