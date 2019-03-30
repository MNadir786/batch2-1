node('maven'){
    stage('CheckOut'){
        echo "Cloning the repository"
        git credentialsId: 'Sanquest-key', url: 'https://github.com/MNadir786/batch2-1'  
    }
    stage('runningScript'){
        
        echo " RunningtheScript"
        sh "sh test.sh"
}
}
