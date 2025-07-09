# Version history

## 1.4.0

Jun 30, 2025

- Power Station now displays an error if the firmware update process is incomplete
- Allow users to check the firmware version of the Power Station and Attached Tools.
- Alert users if Power Station and Iron are not on the same Firmware version
- Improved handling of a completely dead (or missing) battery.
- Fixed bug in which temperature display failed to update during cooldown.

## 1.3.2

May 24, 2025

- Improved handling of a completely dead (or missing) battery

## 1.3.0

Apr 8, 2025

- Added a 'Discharge Slowed' screen for when the Power Station lowers output power due to heat buildup.
- Improved battery error recovery to allow users to bypass non-critical battery states.
- Changed battery charge level reporting to more accurately reflect battery state.

## 1.2.2

Feb 27, 2025

- Reduced erroneous battery errors.
- Improved handling of power-on from dead battery states.

## 1.1.2

Feb 10, 2025

- Improved thermal performance and stability when charging laptops.
- Fixed restart and detection issues when connecting or disconnecting tools.
- Improved power management from discharged battery states.

## 1.0.7

Dec 20, 2024

- Ensured Power Station Rear port charges reliably on USB-A Power Sources.
- Updated user menu options in Power Station UI.
- Enhanced error state recovery for Power Station.

## 1.0.6

Nov 26, 2024

- Turned off front port power during intro animation.
- Forced proper order of front-port power negotiation after recovery or boot.

## 1.0.5

Nov 4, 2024

- Ensured battery overheat warning shows at the correct time.
- Preserved port 2 connection to soldering iron when Power Station is plugged in to power source.
- Slowed the output power display when powering a non-FixHub USB Device.

## 1.0.4

Oct 14, 2024

- Allowed connecting iFixit tool when generic tool is already connected to Power Station.
- Improved stability when powering non-iFixit tools.
- Reduced quiescent power draw when the Power Station is turned off.
- Added the ability to specify the maximum charge percentage of the Power Station.
- Reorganized the Multi-Language menu options.

## 1.0.3

Sep 16, 2024

- Allowed Power Station MCU to determine if a port was available for connection.
- Added feature for Power Station to report generic tool connections to the CLI.

## 1.0.2

Sep 4, 2024

- Updated German translations.
- Improved accuracy of reporting of battery state of charge (SoC) during and after charging.
- Reduced flash space usage.
- Improved quiescent power draw when the Power Station is turned off.
- Changed the numerical display of power output to include tenths of watts.
- Reorganized CLI commands for Power Station power and charging details.
- Enabled charging of the Power Station from non-USB PD power sources.

## 1.0.1

Aug 16, 2024

- Version bump

## 1.0.0

Aug 16, 2024

- Initial Release
