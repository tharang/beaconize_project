# beaconize_project

THIS IS A WORK IN PROGRESS

Estimote beacon's java script apis are defined at https://evomedia.evothings.com/jsdoc/phonegap-estimotebeacons/estimote.html. 
Refer the apis of beacons and nearables.
As of now, the code is supposed to monitor and range all the available beacons(the ones with default UUID). 
The issue I am working on is, the data binding.

This project involves the following
1. Ionic framework and its CLI commands
2. Javascript/HTML/CSS
3. Firebase<yet to to be added, for cloud syncing>
4. Angular jS <yet to to be added, better data binding>

I use atom editor for code browsing/editing.
The ionic commands for developing/debugging are detailed @ http://ionicframework.com/docs/cli/
For quick ionic usage:
1. to start a project: 
    ionic start <app-name> <template>

2.ionic add platform ios
  ionic add platform android

3. to live debug:(VERY USEFUL)
  ionic serve --lab
  
4. build the code:
  ionic build ios
  ionic build android

5. setup AVD in your android tools
  ionic emulate ios
  ionic emulate android

6. run the tested app in your device
  ionic run ios
  ionic run android

  
