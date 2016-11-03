node {
   stage('SCM') { 
     checkout scm
   }
   stage('CocoaPods') {
     sh "pod install"
   }
   stage('Build') {
      sh "xcodebuild -workspace helloworld-ios-app.xcworkspace -scheme helloworld-ios-app"
   }
}
