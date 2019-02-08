# omnistack

Prepare machine:

Install JDK and SDK cli or Android Studio:

Links

JDK:
https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html
Configure your ~/.bash_profile with:

export JAVA_HOME="path that you found"
export PATH=$JAVA_HOME/bin:$PATH

SDK: https://developer.android.com/studio/?hl=pt-br#downloads

Configure your ~/.bash_profile with:

export ANDROID_HOME=~/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/platform-tools

Install virtualbox and genymotion

sudo apt install virtualbox
chmod +x genymotion.bin
./genymotion.bin

Install Node and yarn

Links
Node: (Current Version) https://nodejs.org/en/download/current/

Yarn: https://yarnpkg.com/lang/en/docs/install/

Test:

node -v
yarn -v

Install dependencies:

yarn global add create-react-app
yarn global add react-native-cli
