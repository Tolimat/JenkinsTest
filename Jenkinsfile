pipeline 
{
    agent any
    stages 
    {
        stage('Test') 
        {
            steps 
            {
                sh 'python3 main.py'
            }
        }
        stage('Confirm') 
        {
            steps 
            {
                sh 'echo Pipeline sucess'
            }
        }
    }
}