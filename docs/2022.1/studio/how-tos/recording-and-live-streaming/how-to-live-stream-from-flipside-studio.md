# How to live stream from Flipside Studio

Here's how to live stream from Flipside Studio:

--- Platform: Quest ---

## Requirements

Live streaming requires a PC with [OBS Studio](https://obsproject.com/) installed and configured to stream to your platform of choice.

## Live streaming

**Step 1.** Launch Flipside Studio on your Quest.

**Step 2.** Press the Oculus menu button to open the Dash menu then click on the **Cast** icon.

**Step 3.** Choose **Computer** and click **Next**. Press the Oculus menu button again to close the Dash menu and return to Flipside Studio.

**Step 4.** On your PC, open a web browser and visit `https://oculus.com/casting`. Click on the video settings and ensure the audio sources you want to capture are checked.

**Step 5.** Launch OBS Studio on your PC and add a **Window Capture** source to capture your browser window. Adjust the window capture area so Flipside Studio's camera output properly fills the window capture area.

**Step 6.** Click **Start Streaming** in OBS to start live streaming.

**Step 7.** When you're done live streaming, click **Stop Streaming** in OBS.

--- Platform: Oculus ---

## One-time setup

**Step 1.** Install [OBS Studio](https://obsproject.com/).

**Step 2.** Install the [obs-websocket plugin](https://obsproject.com/forum/resources/obs-websocket-remote-control-obs-studio-from-websockets.466/).

**Step 3.** Launch OBS Studio and Flipside Studio.

**Step 4.** Under the **Sources** section, click the **+** icon and select **Window Capture**. Make sure **Create new** is selected and keep **Make source visible** checked.

Once the source is added, double-click it in the **Sources** section to bring up the Properties pane. In the Properties pane, select **Flipside Studio** in the **Window** dropdown menu. Make sure **Capture Cursor** is unchecked.

**Step 5.** Under **Audio Mixer**, add audio sources for both **Mic/Aux** and **Desktop Audio** to capture both your own voice and sounds coming from Flipside Studio.

Click on the gear icon for the **Mic/Aux** audio source and enter **120** into the **Sync Offset (ms)** field. Note that if you use the obs-websocket plugin and connect Flipside Studio to OBS, this will be set for you automatically.

**Step 6.** Adjust the window capture area so that Flipside Studio's camera output properly fills the window capture area.

## Live streaming

**Step 1.** Press the menu button on either controller and choose **Camera Switcher** from the main menu.

**Step 2.** Press the menu button again and choose **Camera** to add a camera to your set.

**Step 3.** On the camera switcher, click **Connect** to connect to OBS.

**Step 4.** On the camera switcher, click **Stream** to start live streaming.

**Step 5.** When you're done live streaming, click **Stop Streaming** on the camera switcher.

--- Platform: SteamVR ---

## One-time setup

**Step 1.** Install [OBS Studio](https://obsproject.com/).

**Step 2.** Install the [obs-websocket plugin](https://obsproject.com/forum/resources/obs-websocket-remote-control-obs-studio-from-websockets.466/).

**Step 3.** Launch OBS Studio and Flipside Studio.

**Step 4.** Under the **Sources** section, click the **+** icon and select **Window Capture**. Make sure **Create new** is selected and keep **Make source visible** checked.

Once the source is added, double-click it in the **Sources** section to bring up the Properties pane. In the Properties pane, select **Flipside Studio** in the **Window** dropdown menu. Make sure **Capture Cursor** is unchecked.

**Step 5.** Under **Audio Mixer**, add audio sources for both **Mic/Aux** and **Desktop Audio** to capture both your own voice and sounds coming from Flipside Studio.

Click on the gear icon for the **Mic/Aux** audio source and enter **120** into the **Sync Offset (ms)** field. Note that if you use the obs-websocket plugin and connect Flipside Studio to OBS, this will be set for you automatically.

**Step 6.** Adjust the window capture area so that Flipside Studio's camera output properly fills the window capture area.

## Live streaming

**Step 1.** Press the menu button on either controller and choose **Camera Switcher** from the main menu.

**Step 2.** Press the menu button again and choose **Camera** to add a camera to your set.

**Step 3.** On the camera switcher, click **Connect** to connect to OBS.

**Step 4.** On the camera switcher, click **Stream** to start live streaming.

**Step 5.** When you're done live streaming, click **Stop Streaming** on the camera switcher.

--- /Platform ---

---

Back: [[Studio / How tos]]