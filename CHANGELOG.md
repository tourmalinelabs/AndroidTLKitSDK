# TLKit Change Log

# 23.2.25040300
* Several improvements

# 23.0.24052900
* Several improvements

# 23.0.24032100
* Several improvements

# 22.3.23102601
* Several improvements

# 22.3.23101001
* Several improvements

# 22.1.23062602
* Several improvements

# 22.0.23060200
* Several improvements

# 17.4.22052301
* Several improvements

# 17.4.22050403
* Several improvements

# 17.4.22032800
* Several improvements

# 17.4.21122400
* Several improvements

# 17.4.21111500
* Several improvements

# 17.2.21090600
* Several improvements

# 17.1.21082701
* Several improvements

# 17.0.21062900
* Several improvements

# 15.8.20112300
* Several improvements

# 15.6.20100100
* TLKit: fix bug causing incorrect sensor sampling
* TLKit: Hide Off-Duty Trips - clientConfig (TOUR-6500)

# 15.5.20071700
* Several improvements

# 15.5.20062300
* Several improvements

# 15.5.20050400
* Several improvements

# 15.3.20012900
* Several improvements

## 15.0.19110600
* Several improvements

## 14.4.19100200
* Several improvements

## 14.4.19072900
* Several improvements

## 12.0.18061800
* Android P compatibility

## 12.0.18061200
* Several improvements

## 11.6.18052901
* Several improvements

## 11.6.18052500
* Several improvements

## 11.0.17121500
* Realtime telematics service update

## 11.0.17121101
* Realtime telematics service update

## 11.0.17120700
* Realtime telematics service update

## 11.0.17120500
* Realtime telematics service
* APIs to register/unregister as telematics event listener
* APIs to query past telematics events

## 10.3.17110301
* Allows TLKit to start even without location permissions (fix possible missing trips)
* Detect and broadcast power save mode settings update
* Detect and broadcast global device location settings update
* Detect and broadcast application location permission settings update
* Foreground notification ID made public (TLKit users can now dynamically update the foreground service notification)
* Stability improvements.

## 10.1.17083000
* Stability improvements.

## 10.1.17082500
* Stability improvements.

## 10.0.17081400
* Despite major version bump there is no backwards compatibility changes.
* Significant improvement in routing algorithms.
* Stability improvements.
* Fixed bug where trip distance wasn't updated until the trip was complete.

## 9.1.17072100
* Improved stability.

## 9.1.17071700
* Improved stability.
* Reduced network usage.

## 9.0.17062800
* Several improvements
* Fix: no locations events when registering only to the LocationManager

## 9.0.17061900
* SHA-256 hashes of emails now supported as user ids.
* Reworked  `Engine` `Init` methods remove need for standalone authorization
  manager, eliminates seperate methods for starting in manual or automatic
  drive detection:

## 8.1.17051700
* Improved handling for Doze mode in newer versions of Android.
* Route computation improvements
* Battery usage optimizations
* Native 64-bit support:
  * No longer required to exclude 64 bit versions of other libraries
* Fixed bug where location queries would return zero results.

## 8.0.17042000
* Manual monitoring support
  * `Engine.Init` has been renamed to `Engine.InitAutomatic()` and
  `Engine.InitManual()` has been added to allow starting the SDK in the Manual
  mode.
  * `ActivityManager.StartManualTrip()` and `ActivityManager.StopManualTrip()`
  have been added to start and stop manual trips.
  * The monitoring APIs have been removed as they are no longer necessary with the manual trip monitoring functionality.

## 7.2.17041300
* Fix for merging of trips.

## 7.1.17040502
* Fix where monitoring state was not properly initialzed.

## 7.0.17032801
* Fix where some drives were still uploaded even when monitoring was
 turned off.

## 7.0.17032300

* Initial release of TLKit.
* Includes monitoring on/off functionality.
