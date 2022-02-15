pipeline {
    agent any

    stages {
        stage('S3download') {
            steps {
                withAWS(credentials:'aws') {
                    s3Download(file: 'new', bucket: 'delete-1', path: '/root')
                    
                }
                
            }
            
        }
        
    }
}
