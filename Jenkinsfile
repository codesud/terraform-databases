@Library('roboshop-shared-library@main') _

env.REPONAME="terraform-databases"

terraform()







// pipeline {
//     agent any 
//     parameters { choice(name: 'ENV', choices: ['dev', 'prod'], description: 'Select the Environment') }
//     stages {
//         stage('terraform init') {
//             steps {
//                 sh "terrafile -f env-${ENV}/Terrafile"
//                 sh "terraform init -backend-config=env-${ENV}/${ENV}-backend.tfvars"
//             }
//         }

//         stage('terraform plan') {
//             steps {
//                 sh "echo doing a terrafomr plan"
//                 sh "terraform plan -var-file=env-${ENV}/${ENV}.tfvars"
//             }
//         }

//         stage('terraform apply') {
//             steps {
//                 sh "terraform apply -var-file=env-${ENV}/${ENV}.tfvars -auto-approve"
//             }
//         }
//     }
// }