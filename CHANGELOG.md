
# Change Log



## [1.2.4] - 2020-07-06

### Added

- Added support for transmitting character dp point data with length 0.
- Added support for Tuya v2 version protocol.
- Added support for using authorization information managed by the application in Bluetooth channel registration device configuration mode.

### Changed

- Changed the dynamic memory release logic in some event handlers, the previous method may cause the dynamic memory free space to become smaller in extreme scenarios.

### Fixed

- Fixed the bug that the single packet data instruction cannot be parsed.
- Fixed an issue that could not be compiled in the non-Bluetooth channel registered device configuration mode.
- Fixed the bug of test link failure based on Tuya protocol.



## [1.2.3] - 2020-05-19

### Added
- Added support for shared devices.
- Added dp point data reporting API with serial number and processing mode.

### Changed

- Clear the binding information when burning the authorization information, if it exists.




## [1.2.2] - 2020-04-23
### Added
- Added on-demand connection interface.
- Added the interface to get the total size, space and number of events of the scheduling queue under no OS environment.
- Added configuration item to configure whether to use the MAC address of tuya authorization information.
- Added tuya app log interface.

### Changed
- Changed the production test code structure, and remove the application layer header file to obtain the application version number, fingerprint and other information methods.
- Changed the encryption method of ble channel used in production test to support unencrypted transmission.

### Fixed
- Fix a problem that caused a compilation error in the SEGGER Embedded Studio environment.

## [1.2.1] - 2020-03-20
### Changed
- Optimized production test function, added data channel parameters


## [1.2.0] - 2020-03-06
### Added
- New platform memory management port.
- Added gatt send queue.
- New production test interface for customer-defined applications.
- Added tuya app log interface.

### Changed
- The maximum length of dp point array data that can be sent at one time increases to 258.
- Optimize RAM usage.
- Stripping uart general processing functions to customer applications.


## [1.1.0] -
### Added


### Changed


### Fixed

## [1.0.0] -
### Added


### Changed


### Fixed

## [0.3.0] -
### Added


### Changed


### Fixed


## [0.2.0] -
### Added


### Changed


### Fixed

