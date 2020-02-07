pipeline{
    agent any
    stages ('git checkout'){
        stage{
            checkout([$class: 'GitSCM', branches: [[name: '*/primary']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/vikrant1992/maven-project']]])
            echo "git successful"
        }
    }
}

