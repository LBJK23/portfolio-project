pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Достаем код из Git...'
            }
        }
        stage('Build') {
            steps {
                echo 'Собираем CRM...'
                // Здесь позже добавим docker build
                sh 'echo "Build success"'
            }
        }
        stage('Test') {
            steps {
                echo 'Запуск тестов...'
                sh 'echo "Tests passed"'
            }
        }
    }
}
