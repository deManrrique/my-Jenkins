pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                // Clona el repositorio
                sh 'git clone https://github.com/deManrrique/hola-mundo.py.git'
            }
        }

        stage('Hello') {
            steps {
                // Cambia al directorio del repositorio clonado
                dir('hola-mundo.py') {
                    echo 'Hello World'
                }
            }
        }
    }
}
