# ScreenRecord

This is a wrapper for screen recording on iOS with ReplayKit2. 

## Usage

Screen recording is abstracted to a single function 

```
ScreenRecordCoordinator().startRecording(withFileName: "coolScreenRecording1", recordingHandler: { (error) in
            print("Recording in progress")
        }) { (error) in
            print("Recording Complete")
        }
```

## Features

* Automatically adds a `stop recording` overlay to the app, so that the user can stop the recording
* Writes Videos to the documents directory in `Replays` folder


## Contributions

Please feel free to contribute to the project :) 

## License
MIT License