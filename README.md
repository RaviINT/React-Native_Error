# React-Native_Error

#View Pager Error
android/settings.gradle
paste this:
include ':@react-native-community_viewpager'
project(':@react-native-community_viewpager').projectDir = new File(rootProject.projectDir, '../node_modules/@react-native-community/viewpager/android')
