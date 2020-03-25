stage('Checkout external proj') {
        steps {
            git branch: 'master',
                credentialsId: '6b4562bd-e947-4f59-ab5e-4b3f96d1f519',
                url: 'https://github.com/sanjanrahman/terraform-workspace'

            sh "ls -lat"
            sh "cd terraform-workspace/projects/A"
            sh "terraform init" 
            
        }
    } 
