node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}

stage('Get approval'){
    input "Deploy to dev?"
}
node {
    stage('deploy to dev'){
        echo "deploying"
    }
}
