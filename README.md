# Burp Suite macOS Terminal Setup Guide
# Open Terminal and navigate to the app directory
```bash
cd "/Applications/Burp Suite Professional.app/Contents/Resources/app"

# Execute the following command to start the registration machine:

"/Applications/Burp Suite Professional.app/Contents/Resources/jre.bundle/Contents/Home/bin/java" -jar BurpLoaderKeygen.jar
# Modify Configuration,  Edit /Applications/Burp Suite Professional.app/Contents/vmoptions.txt and add the following parameters:

--add-opens=java.base/java.lang=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED
-javaagent:BurpLoaderKeygen.jar
-noverify
