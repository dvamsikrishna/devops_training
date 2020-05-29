pipeline {

    
   agent any
    
    environment {

    CR_Number="${params.CR_Number1}"

    START_DATE1="${params.START_DATE}"
	END_DATE1="${params.END_DATE}"
	
    }

    stages {

    stage ('values') 
	{
	steps {
	
	println "CR_Number : ${CR_Number}"
	println "START_DATE1     : ${START_DATE1}"
	println "END_DATE1     : ${END_DATE1}"
	
	}
	}
	}
	}
