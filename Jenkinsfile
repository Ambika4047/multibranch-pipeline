pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is hotfix branch"'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "This is hotfix branch..."'
            }
        }  
    }
}
