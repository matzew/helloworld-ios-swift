node {
   stage('SCM') { 
     checkout scm
   }
   stage('CocoaPods') {
     sh "pod install"
   }
}
