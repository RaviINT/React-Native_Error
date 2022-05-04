# React-Native_Error

#View Pager Error

In android/settings.gradle

paste this:

include ':@react-native-community_viewpager'
project(':@react-native-community_viewpager').projectDir = new File(rootProject.projectDir, '../node_modules/@react-native-community/viewpager/android')
