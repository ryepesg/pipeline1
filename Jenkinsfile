node {
   
   	stage 'Etapa 1'
   		echo 'Saludo'
   	stage 'Checkout'
   		git url: 'https://github.com/repo/proyecto.git'
   	stage 'Build'
   		sh './build.sh'
   	stage 'Deploy'
   		sh './deployment.sh'
  
}
