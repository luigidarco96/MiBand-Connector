# MiBand-Connector

Android Library to connect an app with a Xiaomi Mi Band 3 using the BLE

## Integration

To get this library in your project using the grandle:

**Step 1.** Add the JitPack repository to your build file (build.grandle(Project)), at the end of repositories section

```Java
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

**Step 2.** Add the dependency in the modules build file (build.grandle(Module)), in the dependencies section

```Java
dependencies {
  implementation 'com.github.luigidarco96:MiBand-Connector:1.0.0'
}
```
