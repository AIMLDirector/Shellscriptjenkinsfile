node {
   
   	stage 'Stage 1'
   		echo 'Node method Deployment'
   	stage 'Checkout'
   		git url: 'https://github.com/premkumar-1979/Shellscriptjenkinsfile.git'
   	stage 'Build'
   		sh './Dev.sh'
   	stage 'Deploy'
   		sh './Test.sh'
  
}

