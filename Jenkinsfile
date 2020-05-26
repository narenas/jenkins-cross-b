pipeline { 
    agent any 

    stages { 
        stage('Example') {
            steps {
                echo 'Launch CI'
                sh "chmod 755 launch.sh && ./launch.sh"
                publishEvent simpleEvent('SimpleTrigger')
            }
        }
    }   
}