def projectname="basic project"
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


 		 stage("printing_project_name") {
			  steps{
					 script { 
							 echo "_________________printing a project name _______" 
							  echo "${projectname}"

						 }	 

			  } 

		 }



			 stage ("functional_stage"){
			steps{
			       script  { 
					    def a  = 122  
						echo ${a}
				   }
			}
		 }




	}


}
