continuous_integration()
deploy_to dev

if(requiresApproval){
    timeout(time: 5, unit: 'MINUTES'){
        input 'Approve the deployment?'
    }
}

deploy_to prod