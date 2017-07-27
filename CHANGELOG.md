# TLKit Change Log

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
