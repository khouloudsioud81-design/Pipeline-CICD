pipeline { agent any

stages {
    stage('Checkout') {
        steps {
            echo 'Code récupéré depuis GitHub'
        }
    }

    stage('Build') {
        steps {
            echo 'BUILD EN COURS...'
        }
    }

    stage('Tests') {
        steps {
            echo 'EXECUTION DES TESTS...'
        }
    }

    stage('Qualité') {
        steps {
            echo 'ANALYSE DE QUALITE...'
        }
    }

    stage('Build Docker') {
        steps {
            echo 'BUILD DOCKER...'
        }
    }

    stage('Déploiement') {
        steps {
            echo 'DEPLOIEMENT...'
        }
    }
}


}
