pipeline{

    agent any

    environment {
        DIRECTORY_PATH = "${env.WORKSPACE}"
        AUTOMATION_TOOL = 'Maven'
        UNIT_TESTING_TOOL = 'JUnit'
        INTEGRATION_TESTING_TOOL = 'Robot Framework'
        ANALYSIS_TOOL = 'SonarQube'
        SECURITY_TOOL = 'OWASP ZAP (Zed Attack Proxy)'
        STAGING_SERVER = 'AWS (Amazon Web Services) staging server'
        STAGING_ENVIRONMENT = 'staging environment'
        PRODUCTION_SERVER = 'AWS (Amazon Web Services) production server'
    }

    stages {

        stage("Build") {

            steps {
                echo "Fetch the source code from the directory path: ${DIRECTORY_PATH}."
                echo "Compile the code package the code using ${AUTOMATION_TOOL}."
            }

        }
        
    }
    
}
