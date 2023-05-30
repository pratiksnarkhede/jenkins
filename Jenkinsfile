pipeline {
    agent any
    
    stages {
        stage('Install Python') {
            steps {
                sh 'apt-get update' // Update package lists (for Debian-based systems)
                sh 'apt-get install -y python3' // Install Python 3
                
                // You can also install additional Python packages using pip:
                sh 'pip install <package_name>'
                
                // If you're working on a Windows machine, you can use chocolatey to install Python:
                // bat 'choco install python3'
            }
        }
        
        stage('Build') {
            // Add your build steps here
        }
        
        // Add more stages as needed
    }
}
