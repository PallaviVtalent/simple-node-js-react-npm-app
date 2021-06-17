pipeline 
{
agent { 
label 'newone'
}
stages {
  stage  ('checkout')
 {
 steps { 
         checkout scm
   }
 } 
  stage ( 'Build')
 {
 steps { 
         sh "cd /root/angular; npm install"
}
}
}
}
