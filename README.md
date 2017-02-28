### Add the following to your top level gradle file:

Based off https://github.com/saki4510t/UVCCamera

``` ext {
	supportLibVersion = '25.1.0'  // variable that can be referenced to keep support libs consistent
	commonLibVersion= '1.4.3'
	versionBuildTool = '25.0.2'
	versionCompiler = 25
	versionTarget = 23
	versionNameString = '1.0.0'
	javaSourceCompatibility = JavaVersion.VERSION_1_7
	javaTargetCompatibility = JavaVersion.VERSION_1_7
}
```
