continuous_integration()
deploy_to dev

if(requiresApproval){
    timeout(time: 5, unit: 'MINUTES') {
        input 'Approve this deployment?'
    }
}

deploy_to prod
