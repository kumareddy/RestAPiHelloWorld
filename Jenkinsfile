
pipeline{

     agent any
      
     stages{
     stage('CheckoutCodefromScm')
{
      steps{

      git 'https://github.com/kirankurakugit/RestApiHelloWorld.git'

     echo "checkoutcode from scm"
    }
    }
    
   stage('Build'){
    steps{
   mvn clean package
  echo "buiild
    }
     
   
}
