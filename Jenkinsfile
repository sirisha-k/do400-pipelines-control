 {
    AGENT {
        NODE {
            label 'nodejs'
        }
    }
    STAGES {
        STAGE('bACKEND tESTS') {
            STEPS {
                SH 'NODE ./BACKEND/TEST.JS'
            }
        }
        STAGE('fRONTEND tESTS') {
            STEPS {
                SH 'NODE ./FRONTEND/TEST.JS'
            }
        }
    }
}