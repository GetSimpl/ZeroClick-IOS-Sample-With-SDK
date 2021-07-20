# ZeroClick-IOS-Sample-With-SDK

Demo IOS application to showcase ios sdk integration

## Testing SDks

To test the updated SDK, open  GetSimpl.xcodeproj from simpl-ios-sdk-ios7 and select scheme any one scheme

1. SimplOneClickUniversal
2. GetSimplUniversal
3. SimplZeroClickUniversal
4. SimplFingerPrintUniversal

Edit the scheme, In Run -> Change the build configuration to Release. Then Click on the run button. Once build is succeeded. Goto the derived data from location tab.

Go to this location from your finder
/Users/XXXX/Library/Developer/Xcode/DerivedData/GetSimpl-XXXX/Build/Products

Three folders are created
1. Release-iphoneos
2. Release-iphonesimulator
3. Release-universal

In which the corresponding SDk's.framework folder is created.

Open simpl-demo-app-with-sdk-ios.xcodeproj in Xcode

On left side Tab, delete the existing .frameworks inside the Framework folder.

Add the SDk's.framework from the Release-universal or Release-iphonesimulator and run the project in the simulator