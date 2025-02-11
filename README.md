# Pangle iOS SDK
Pangle iOS SDK for Swift Package Manager.

# Integration
The Swift Package Manager is a tool for managing the distribution of Swift code. It’s integrated with the Swift build system to automate the process of downloading, compiling, and linking dependencies.
To integrate the Pangle SDK into your project using Swift Package Manager:
1. Add it to the dependencies of your Package.swift:
```objc
    dependencies: [
        .package(url: "https://github.com/serasateam/GoogleMobileAdsMediationPangle", .exact("6.3.1-release.2"))
    ]
```
2. Enable the `-ObjC` flag in Xcode: select Build Settings, search for Other Linker Flags and add `-ObjC`.

3. Check and add if necessary in your project, [Google Mobile Ads Adapter](https://developers.google.com/admob/ios/mediation/pangle#pangle-ios-mediation-adapter-changelog).

Check out our [integration docs](https://www.pangleglobal.com/zh/integration/integrate-pangle-sdk-for-ios) for more info on getting started with Pangle SDK.

## Author

denys.galante, denys.galante@br.experian.com