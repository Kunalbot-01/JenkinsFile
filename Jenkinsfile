pipeline {
    agent any
    stages{
        stage('Check Disk Usage') {
            steps {
            
             echo "------IO Wait---------------------------------"
             sh "iostat -c 2 2"
             echo "------Disk Useage---------------------------------" 
             sh "df -kh"
        }
         
        }
    }
        

}
