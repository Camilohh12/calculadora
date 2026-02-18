pipeline {
    agent any

    stages {
        stage('Clonar') {
            steps {
                echo 'Clonando repositorio...'
            }
        }

        stage('Compilar / Verificar') {
            steps {
                bat 'dir'
            }
        }

        stage('Finalizado') {
            steps {
                echo 'Build exitoso'
            }
        }
    }
}
