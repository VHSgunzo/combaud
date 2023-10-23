# combaud
Broadcasting audio output from applications to a virtual microphone.

## Usage:
```
$ combaud {args} {app app...}

--help  |-h              Show this usage info
--loop  |-l {app app...} Capture apps to the mic in a loop
--del   |-d {app app...} Remove apps from the mic capture
--stop  |-s              Stop the capture
```

## **Environment variables:**
* `LOOP_SLEEP`          - Capture loop waiting time (Def: `5`)
* `SINK_NAME`           - Name of the combaud sink (Def: `CombaudSink`)
* `MIC_SOURCE`          - Name of the system mic (Def: `TUI`)
* `VIRTUAL_MIC_NAME`    - Name of the combaud mic (Def: `CombaudMic`)
* `LOOP_IGNORE_LIST_FL` - The path to the loop ignore file [loop-ignore.list](https://github.com/VHSgunzo/combaud/blob/main/loop-ignore.list)
