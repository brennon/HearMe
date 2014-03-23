# HearMe

## Instructions

### Before Experiment (Before Subject Arrives)

- Ensure that all 9V batteries are fully charged.
- Connect sensors to Wi-microDig. Connect EDA sensor to input 0 and ECG sensor to input 1.
- Connect 9V battery to Wi-microDig.
- Open `setup_test` patch.
- Click the play button to start the patch.
- Wait several seconds for the patch to fully initialize.
- Sensor Data
  - Click "Connect to Sensor".
  - Once blue LED illuminates and indicator on microDig block turns green, click "Start Data Streaming from Sensor".
  - If blue LED does not illuminate or block indicator does not turn green, confirm that the selected COM port in the microDig block properties matches that shown for the Bluetooth device by Windows.
  - Visually confirm with the visualization that data is flowing.
  - Click "Stop Streaming Data from Sensor".
  - Click "Disconnect from Sensor".
- Audio/Video Playback
  - Click "Play". Confirm that both audio and video playback.
  - Click "Stop".
- Video Recording
  - Confirm that a live camera image is being displayed.
  - Adjust focus/zoom of camera as necessary.
  - Visually confirm with visualization that sound from the microphone is being received.
- Click stop to stop patch.
- Close EyesWeb.
- Disconnect 9V battery from transmitter.
- Sterilize sensor electrodes.

### Before Experiment (After Subject Arrives)

- Attach sensors to subject.
- Connect 9V battery to Wi-microDig.
- Open EyesWeb patch.
- In EyesWeb, set subject number in the patch's "Session Metadata" section.

### Before Each Phase (In EyesWeb)

- Set phase number in the "Session Metadata" section.
- Click the play button to start the patch.
- Wait several seconds for the patch to fully initialize.
- Click "Connect to Sensor".
- Once blue LED illuminates and indicator on microDig block turns green, click "Start Data Streaming from Sensor".
- If blue LED does not illuminate or block indicator does not turn green, confirm that the selected COM port in the microDig block properties matches that shown for the Bluetooth device by Windows.
- Open "Sensor Data Visualization" subpatch. Confirm that signals are streaming.
- Open the video recording preview. Confirm that the camera is properly aimed and zoomed. Confirm that the correct subject and phase number is displayed.
- If the subject or phase number are incorrect, stop the patch, adjust these numbers in the "Session Metadata" section, and follow instructions from the beginning of this section.

### After Each Phase

- Click "Stop Data Streaming from Sensor".
- Click "Disconnect from Sensor".
- When the blue LED on the sensor is no longer illuminated, click stop to stop the EyesWeb patch.
- Confirm that the physiology, event, and video datafiles have been successfully recorded and saved.

### Phase I

- Follow steps in *Before Each Phase (In EyesWeb)*.
- As phase progresses, click the appropriate buttons in the "Event Recording" section of the patch to mark events as they occur.
- Follow steps in *After Each Phase*.

### Phase II

- Follow steps in *Before Each Phase (In EyesWeb)*.
- Click the "Begin audio/video playback" button to begin playback of Phase II media.
- As phase progresses, click the appropriate buttons in the "Event Recording" section of the patch to mark events as they occur.
- Follow steps in *After Each Phase*.

### Phase III

- Follow steps in *Before Each Phase (In EyesWeb)*.
- When appropriate, click the "Begin ____ sound - ____" buttons to play the appropriate sound files.
- As phase progresses, click the appropriate buttons in the "Event Recording" section of the patch to mark events as they occur.
- Follow steps in *After Each Phase*.
