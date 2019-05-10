# Flutter Rx BLE

A Flutter BLE plugin, based on [RxAndroidBle](https://github.com/Polidea/RxAndroidBle) and [RxBluetoothKit](https://github.com/Polidea/RxBluetoothKit) libraries.

### Batteries included.

- Acquire every permission and setting required for Bluetooth access, 
using a _single_ method - `RxBle.requestAccess()`. 
- No need to manually discover BLE services.
- Automatically queue up GATT requests to avoid race conditions.