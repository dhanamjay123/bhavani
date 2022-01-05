
pipeline {
agent {
label 'jenkins004'
}

stages {

stage ('Checkout') 
{
steps
    {
    
        checkout scm
        
    }
    
}
stage ('sucessfullexcution') 
{
    steps {
        node('ramraj'){
        echo "checkout has been done"
        }        
    }

}
}

}
