pipeline {
    agent any  // Executa a qualsevol agent disponible

    stages {

        stage('Checkout') {
            steps {
                sh 'ls -la'  // Llista els fitxers per confirmar que s'han descarregat
                echo '¡Codi descarregat automàticament!'
            }
        }

        stage('Build') {
            steps {
                echo 'Simulant compilació...'
            }
        }

    }
}
