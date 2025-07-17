# Camera calibration (distortion correction) tutorial

This tutorial describes how to use the checkerboard_calib and calibrate_camera functions to correct camera distortions.

[![test-pr](https://github.com/danforthcenter/plantcv-tutorial-camera-calibration/actions/workflows/ci-tests.yml/badge.svg)](https://github.com/danforthcenter/plantcv-tutorial-camera-calibration/actions/workflows/ci-tests.yml)

Check out our interactive tutorial!

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/danforthcenter/plantcv-tutorial-camera-calibration.git/HEAD)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danforthcenter/plantcv-tutorial-camera-calibration/blob/main/index-Colab.ipynb)

## Google Colaboratory Users: Clone this repository to your Google Drive
1. Install and add [Google Colaboratory](https://workspace.google.com/u/1/marketplace/app/colaboratory/1014160490159?pann=ogb) to your Google Workspace.
2. Open [Google Drive](drive.google.com) in your web browser.
3. Open a new Google Colaboratory notebook (.ipynb):
   * +New (Found above menu on the left side of the screen).
   * In the menu, select **More**.
   * Select *Google Colaboratory* in the second menu.
   * NOTE: If you do not see *Google Colaboratory* in the second menu, you may need to refresh the web page.
5. Add the following code in the first cell:
```
# Mount your Google Drive to Google Colaboratory
from google.colab import drive
drive.mount('/content/gdrive')
# Change your working directory to the mounted drive
%cd gdrive/MyDrive/
# Print the contents of your drive to confirm it worked
!ls
# Clone the workshop's repository to your Google Drive
!git clone https://github.com/danforthcenter/plantcv-tutorial-camera-calibration.git
```
5. Run the cell either by hitting the **Play** button or by pressing *Shift + Enter*
6. You may get a dialog box warning you that the notebook isn't authored by Google, select **Run Anyway**.
7. You will be prompted by another dialog box asking for permission to access your Google Drive within the notebook, select **Connect to Google Drive**.
8. You should see the contents of your Google Drive printed below.
9. Check your Google Drive to see if you have a new directory named plantcv-tutorial-camera-calibration and that all of the contents from this repo should be within.

## Tutorial tags/keywords

calibration, transform, checkerboard, distortion, RGB, tutorial
