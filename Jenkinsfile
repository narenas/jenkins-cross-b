pipeline { 
    agent any 

    stages { 
        stage('Example') {
            steps {
                echo 'Launch CI'
                sh "./launch.sh"
                publishEvent simpleEvent('SimpleTrigger')
            }
        }
    }   
}