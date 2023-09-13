Checking build time with cache.
To do so we removed `kotlin.native.cacheKind=none` from [gradle.properties](gradle.properties)

checked with gradle task `./gradlew :shared:linkDebugFrameworkIosSimulatorArm64`

 - previously witj Kotlin 1.9.10 and `kotlin.native.cacheKind=none` it takes 
 - with Kotlin 1.9.20 and cache it takes **22s**