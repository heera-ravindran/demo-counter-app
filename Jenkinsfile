pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/heera-ravindran/demo-counter-app.git'
                }
            }
        }
        
        }
        
}
