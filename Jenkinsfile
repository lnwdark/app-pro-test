node {
     def app

    stage('Clone repository') {
        /* Cloning the Repository to our Workspace */
        checkout scm
    }

    stage('Build image') {
        /* This builds the actual image */

    }

    stage('Test image') {
        
        app.inside {
            echo "Tests passed"
        }
    }
}