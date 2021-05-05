//Pipeline declarativo
pipeline {
    
    //ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    // Fases
    stages {        
        stage('Build'){            
            //pasos de la fase
            steps{
                    echo "Building artifact"
            }            
        }
        
        stage('Testing'){            
            //pasos de la fase
            steps{
                    echo "Test unitarios"
                    echo "Test integracion"
                    echo "Test aceptacion"
            }            
        }
        
        stage('Deploy'){            
            //pasos de la fase
            steps{
                    echo "Desplegando artefacto"
            }            
        }        
    }
    
}
