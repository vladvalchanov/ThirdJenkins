pipeline {
 agent any
  stages {
    stage('Build') {
        steps {
            script {
                    def today = new Date()
                    def tomorrow = today + 1
                    def dayaftertomorrow = tomorrow + 1
                    println "Today: " + today.format("MM/dd/yyyy") + " && Tomorrow: " +
                    tomorrow.format("MM/dd/yyyy") + " && The Day after tomorrow: " +
                    dayaftertomorrow.format("MM/dd/yyyy")
                } 
            }
        }
    }
}
