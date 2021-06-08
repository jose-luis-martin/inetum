//pipeline declarativo
pipeline{
    
    //especificar en que agente se va a ejecutar
    //en nuestro caso cualquiera
    agent any
    stages{
    //definicion de fases
    stage("Stage 1 Build"){
        //pasos de la fase cmd, script o codigo de terceros
        steps{
            echo "Fase 1 de Stage Build";
        }
    }
    
    stage("Stage 2 Test"){
        //pasos de la fase cmd, script o codigo de terceros
        steps{
            echo "Running unit test";
            echo "Running integration test";
            echo "Running aceptation test";
        }
    }
    
    stage("Stage 3 Deploy"){
        //pasos de la fase cmd, script o codigo de terceros
        steps{
            echo "Deploying artifact";
            
        }
    }
    
    }
}
