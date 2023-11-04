pipeline{

    agent any
    stages{
        stage("Console Output"){
            steps {
                echo "Hello Jenkins!"
            }
        }

        stage("Trigger file"){
            steps {
                sh "python3 Hello_jenkins.py"
            }
        }

    }        
}
