
pipeline{
	agent any
	stages{
           stage ("build") {
                         steps{
					sh 'echo "hello this is from the build scripti"'
        			}
		} 



		stage ("condition verification"){
			    steps { 
					   script {
						def a =12 
						   if (a==12)
						      { 
								 echo "condition verified"
							  }
							  else {
								echo "unable to verify the condition"
							  }
					   }
				}
		 }

	}


}
