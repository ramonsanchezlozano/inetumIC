//Pipeline declarativo
pipeline{
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    // Fases
    stages{
        stage('Fase Build'){
            //Pasos de la fase
            steps{
                echo "Building artifact..."
            }
        }
        
        stage('Fase Testing'){
            //Pasos de la fase
            steps{
                echo "Test Unitarios..."
                echo "Test Integración..."
                echo "Test Aceptación..."
            }
        }
        
        stage('Fase Deploy'){
            //Pasos de la fase
            steps{
                echo "Deploy artifact..."
            }
        }
    }
}
