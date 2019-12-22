[MCVE](https://stackoverflow.com/help/minimal-reproducible-example) for https://stackoverflow.com/questions/59441042/secure-spring-boot-application-with-public-key-only

# How to run
1. Create keystore file using this command:

`keytool -genkeypair -keyalg RSA -alias selfsigned -keystore keystore.jks -storepass password -validity 360 -keysize 2048`

2. Update files in `resources`

3. Run `DemoApplication`
 