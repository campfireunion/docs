# How to live stream from Flipside

Here are the steps to live stream from Flipside.

## Requirements

Live streaming requires a PC with the following software installed and configured to stream to your platform(s) of choice. Follow the steps in the one-time setup for each app and from then on you can skip straight to the [live streaming steps](#live-streaming).

- [Flipside Broadcaster](/docs/broadcaster)
- [OBS Studio](https://obsproject.com/)

> **Note:** If you're using the desktop version of Flipside, you can skip using Flipside Broadcaster and capture Flipside directly in OBS, unless you want to capture on a separate machine than the one you're using for VR.

## One-time setup

### Flipside Broadcaster setup

>**Note:** You only need to set up Flipside Broadcaster once.  If you've done it already, skip to the **Live streaming** section.

**Step 1.** Install Flipside Broadcaster on your PC.

**Step 2.** Launch Flipside Broadcaster and click on the **Settings** icon in the top right of the room code window.

:gif https://flipside.nyc3.cdn.digitaloceanspaces.com/docs/2023.1/help_Flipside-Broadscaster_settings.mp4 

**Step 3.** Click **Install** to install the Flipside Broadcaster virtual camera. Click **OK** when prompted by the installer.

:gif https://flipside.nyc3.cdn.digitaloceanspaces.com/docs/2023.1/help_Flipside-Broadcaster_installing-virtual-camera.mp4

**Step 4.** Once the install process has finished, click **Start** to start the virtual camera.

:gif https://flipside.nyc3.cdn.digitaloceanspaces.com/docs/2023.1/help_Flipside-Broadcaster_starting-virtual-camera.mp4

### OBS Studio setup


>**Note:** The **cast** button can also be found on the **main menu**.
>**Note:** You only need to set up Flipside Broadcaster once.  If you've done it already, skip to the **Live streaming** section.

**Step 1.** Install OBS Studio on your PC.

**Step 2.** Click on the **+** icon in the **Sources** panel and choose **Video Capture Device** to create a new video capture source. Name it **Flipside Broadcaster** then click **OK**.

>**Note:** If you run into any issues with adding a **Video Capture Device**, instead you can add Flipside Broadcaster as a capture window in OBS using **Game Capture** as the source.

**Step 3.** Select **Flipside Broadcaster** from the list of devices then click **OK** again.

**Step 4.** Adjust the volume of the **Desktop Audio** source in the **Audio Mixer** section to ensure voices and audio coming from Flipside Broadcaster will be heard in OBS.

## Live streaming

After completing the one-time steps above, here are the steps you can use to start a new live stream from Flipside.

> **Note:** If you're using the desktop version of Flipside, you can skip to **Step 4.** and capture Flipside directly in OBS, unless you want to stream from a separate machine than the one you're using for VR.

**Step 1.** Press the menu button on either controller and choose **Camera Switcher** from the main menu.

:gif https://flipside.nyc3.cdn.digitaloceanspaces.com/docs/2023.1/help_10-3_5_web-edit.mp4

**Step 2.** Press the **Start Cast** button in the bottom left corner of the camera switcher. A popup window will appear with a room code to enter into Flipside Broadcaster to connect.

:gif https://flipside.nyc3.cdn.digitaloceanspaces.com/docs/2023.1/help_10-3_6.mp4

>**Note:** The **cast** button can also be found on the **main menu**.

**Step 3.** Launch Flipside Broadcaster on your PC. Click the settings icon to start the Virtual Camera if it's not already connected. 

:gif https://flipside.nyc3.cdn.digitaloceanspaces.com/docs/2023.1/help_Flipside-Broadcaster_starting-virtual-camera.mp4

Close the settings window then enter the room code you were given in step 2 and click **Connect**.

:gif https://flipside.nyc3.cdn.digitaloceanspaces.com/docs/2023.1/help_10-3_7.mp4

**Step 4.** Launch OBS Studio on your PC and click **Start Streaming** to begin streaming your Flipside Broadcaster output to the world.

**Step 5.** When you're done live streaming, click **Stop Cast** on the camera switcher in Flipside to stop broadcasting to Flipside Broadcaster and click **Stop Streaming** in OBS to stop streaming to the world.

---

**Next:** [[:How to control OBS from Flipside]]
