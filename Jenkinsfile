
pipeline{
            agent any
             stages{
               stage('buid') {
                 steps {
                   sh 'echo "Hello World"'
                   sh '''
                        echo "Multiline shell steps works too"
                        ls -lah
                        '''
                 }
               }
             }
}
