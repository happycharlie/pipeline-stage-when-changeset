pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset glob: "*.js"
				//changeset glob: "*WORLD.js", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
