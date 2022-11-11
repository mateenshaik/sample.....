pipeline {
    agent any
    
    stages{
       stage('hello')
           steps{ 
               sh 'echo hello1'
  }
}
   
       stage('sleep') {
           steps{ 
               sh 'sleep 60'
  }
}
     
       stage('hello2'){
           steps{ 
               sh 'echo hello2'
  }
}
    stage('sleep') {
           steps{ 
               sh 'sleep 60'

  }
}
     
       stage('hello3'){
           steps{ 
               sh 'echo hello3'

  }
}
}
}
