pipeline{
    agent any
    stages{
        stage('Build'){
            // steps{
            //     echo "This is the building stages "
            //     sh """
            //         docker -v
            //         ls -lrt


            //         docker run hello-world
            //         echo  "Showing all the dockage images " 
            //         docker images 

            //         echo "Building the image of this project " 
            //         docker build -t reactjs-nginx . 
            //         docker images | grep 'reactjs-nginx'
            //     """
            // }
            steps{
                sh """
                    echo "This is trigger by webhook " 
                    docker compose version 
                

                """
            }
        }

    }
}