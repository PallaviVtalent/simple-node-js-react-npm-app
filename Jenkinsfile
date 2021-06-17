pipeline {
agent { 
label 'newone'
}
stages {
  stage ( ' checkout ')
 {
 steps { 
         checkout scm
   }
}
}

stages {
  stage ( 'Build')
 {
 steps { 
         sh 'mvn clean install'
   }
}
}
}

