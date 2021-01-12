node {
  try {
    def scmVars
    stage('Checkout'){
        scmVars = checkout scm
    }
    def branchName = scmVars.GIT_BRANCH

    stage('pipeline test') {
      echo "${branchName}"
    }


  } catch(e) {

  }
}
