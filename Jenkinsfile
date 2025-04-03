pipeline {
    agent {label 'nodo_agente'}

    stages {
        stage('Build') {
            steps {
                echo 'Construyendo la app....'
            }
        }
        stage('Test') {
            steps {
                echo 'Realizando las pruebas.....'
            }
        }
        stage('Terminar') {
            steps {
                echo 'Limpinando...'
                echo 'Haciendo deploy'
                echo 'Pipeline finalizada'
            }
        }
    }
}

